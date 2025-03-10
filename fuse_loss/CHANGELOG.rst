^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package fuse_loss
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.5.0 (2022-02-23)
------------------
* Adding doxygen to all packages (#241)
* Contributors: Tom Moore

0.6.0 (2023-02-22)
------------------
* 0.5.0
* Update changelogs
* Adding doxygen to all packages (#241)
* Contributors: Gary Servin, Tom Moore

0.7.0 (2023-09-25)
------------------
* Update devel to build on Ubuntu Jammy (22.04) (#326)
  * Update to C++17 for use with Ubuntu Jammy
  * Include Rviz and Eigen as system includes, which supresses warnings within the included libraries
  * use pluginlib and class_list_macros .hpp include instead of deprecated .h From: Lucas Walter <wsacul@gmail.com>
* 0.6.0
* Update changelogs
* 0.5.0
* Update changelogs
* Adding doxygen to all packages (#241)
* Contributors: Gary Servin, Stephen Williams, Tom Moore

0.9.0 (2024-06-17)
------------------
* Support gcc12 and ceres 2.1.0 (#341)
  Add support for the Manifold class when using Ceres Solver version 2.1.0 and above
  ---------
  Co-authored-by: Jake McLaughlin <jake.mclaughlin98@gmail.com>
* Contributors: Enrique Fernandez Perdomo

0.8.0 (2024-02-02)
------------------
* Fix Qwt deprecated declarations (#356)
* 0.7.0
* Update changelogs
* Update devel to build on Ubuntu Jammy (22.04) (#326)
  * Update to C++17 for use with Ubuntu Jammy
  * Include Rviz and Eigen as system includes, which supresses warnings within the included libraries
  * use pluginlib and class_list_macros .hpp include instead of deprecated .h From: Lucas Walter <wsacul@gmail.com>
* 0.6.0
* Update changelogs
* 0.5.0
* Update changelogs
* Adding doxygen to all packages (#241)
* Contributors: Enrique Fernandez Perdomo, Gary Servin, Stephen Williams, Tom Moore

0.4.2 (2021-07-20)
------------------
* Adding roslint dependency to fuse_viz (`#231 <https://github.com/locusrobotics/fuse/issues/231>`_)
  * Adding roslint dependency to fuse_viz
  * Silence CMP0048 warnings
* Contributors: Tom Moore

0.4.1 (2021-07-13)
------------------
* Changelogs
* Fix roslint 0.12.0 (`#186 <https://github.com/locusrobotics/fuse/issues/186>`_)
  * Fix roslint 0.12.0 include_what_you_use warnings
  Mostly for:
  * std::move -> #include <utility>
  * std::make_shared and similar -> #include <memory>
  * Remove static string variable not permitted by roslint 0.12.0, using a test fixture where needed.
* Replace ignition_sensors list param with ignition field (`#163 <https://github.com/locusrobotics/fuse/issues/163>`_)
  * Remove ignition_sensors param and use a per-sensor ignition field
* Add ComposedLoss (`#170 <https://github.com/locusrobotics/fuse/issues/170>`_)
* Patch Tukey loss for Ceres < 2.0.0 (`#159 <https://github.com/locusrobotics/fuse/issues/159>`_)
  * Patch Tukey loss for Ceres < 2.0.0
  * Create ceres_macros.h header
* Plot loss (`#143 <https://github.com/locusrobotics/fuse/issues/143>`_)
  * Add test to plot loss rho, influence and weight
  * Add BUILD_WITH_PLOT_TESTS option (defaults OFF)
* Remove Pseudo-Huber loss, it duplicates SoftLOne (`#152 <https://github.com/locusrobotics/fuse/issues/152>`_)
  * Remove Pseudo-Huber loss, it duplicates SoftLOne
* Add new loss functions (`#142 <https://github.com/locusrobotics/fuse/issues/142>`_)
  The following loss functions, not available in Ceres solver are
  provided:
  * Geman-McClure
  * DCS (Dynamic Covariance Scaling)
  * Fair
  * Pseudo-Huber
  * Welsch
* Support ScaledLoss (`#141 <https://github.com/locusrobotics/fuse/issues/141>`_)
* Add fuse_loss pkg with plugin-based loss functions (`#118 <https://github.com/locusrobotics/fuse/issues/118>`_)
* Contributors: Enrique Fernandez Perdomo, Stephen Williams, Tom Moore

* Fix roslint 0.12.0 (`#186 <https://github.com/locusrobotics/fuse/issues/186>`_)
  * Fix roslint 0.12.0 include_what_you_use warnings
  Mostly for:
  * std::move -> #include <utility>
  * std::make_shared and similar -> #include <memory>
  * Remove static string variable not permitted by roslint 0.12.0, using a test fixture where needed.
* Replace ignition_sensors list param with ignition field (`#163 <https://github.com/locusrobotics/fuse/issues/163>`_)
  * Remove ignition_sensors param and use a per-sensor ignition field
* Add ComposedLoss (`#170 <https://github.com/locusrobotics/fuse/issues/170>`_)
* Patch Tukey loss for Ceres < 2.0.0 (`#159 <https://github.com/locusrobotics/fuse/issues/159>`_)
  * Patch Tukey loss for Ceres < 2.0.0
  * Create ceres_macros.h header
* Plot loss (`#143 <https://github.com/locusrobotics/fuse/issues/143>`_)
  * Add test to plot loss rho, influence and weight
  * Add BUILD_WITH_PLOT_TESTS option (defaults OFF)
* Remove Pseudo-Huber loss, it duplicates SoftLOne (`#152 <https://github.com/locusrobotics/fuse/issues/152>`_)
  * Remove Pseudo-Huber loss, it duplicates SoftLOne
* Add new loss functions (`#142 <https://github.com/locusrobotics/fuse/issues/142>`_)
  The following loss functions, not available in Ceres solver are
  provided:
  * Geman-McClure
  * DCS (Dynamic Covariance Scaling)
  * Fair
  * Pseudo-Huber
  * Welsch
* Support ScaledLoss (`#141 <https://github.com/locusrobotics/fuse/issues/141>`_)
* Add fuse_loss pkg with plugin-based loss functions (`#118 <https://github.com/locusrobotics/fuse/issues/118>`_)
* Contributors: Enrique Fernandez Perdomo, Stephen Williams

0.4.0 (2019-07-12)
------------------

0.3.0 (2019-03-18)
------------------

0.2.0 (2019-01-16)
------------------

0.1.1 (2018-08-15)
------------------

0.1.0 (2018-08-12)
------------------

0.0.2 (2018-07-16)
------------------

0.0.1 (2018-07-05)
------------------
