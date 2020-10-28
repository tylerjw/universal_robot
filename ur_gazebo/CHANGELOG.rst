^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package ur_gazebo
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.2.8 (2020-10-28)
------------------
* Merge remote-tracking branch 'origin/melodic-devel' into calibration_devel
* migrated all package.xml files to format=2 (`#439 <https://github.com/davetcoleman/universal_robot/issues/439>`_)
* Load the JointGroupPositionController so jog commands can be sent (`#422 <https://github.com/davetcoleman/universal_robot/issues/422>`_)
  * Load the JointGroupPositionController so jog commands can be sent
  * Load new controllers for UR5/UR10, too
  * Add other controllers in launch file
  * Add JointGroupPositionController to UR e-series
* 1.2.5
* Update changelogs. (`#418 <https://github.com/davetcoleman/universal_robot/issues/418>`_)
* Update maintainer listing: add Miguel (`#410 <https://github.com/davetcoleman/universal_robot/issues/410>`_)
  * Add Migual Prada as maintainer.
  * Sort maintainers alphabetically.
  * Fix maintainers and author listing in all e-series pkgs.
  Was missing from `#380 <https://github.com/davetcoleman/universal_robot/issues/380>`_.
* UR-E Series (`#380 <https://github.com/davetcoleman/universal_robot/issues/380>`_)
  * Added meshes for E series as well as gazebo and descriptions
  * Added example MoveIt! configs for the E-series arms
  * updated default planner for moveit config
  * Updated metapackage
  * Updated urE ambiance so gazebo looks right
  * e_description: add proper collision models.
  Simple convex hulls for now, but these could be replaced with more
  advanced convex decompositions in later PRs.
* Merge branch 'kinetic-devel' into mesh-brightness
* Merge pull request `#387 <https://github.com/davetcoleman/universal_robot/issues/387>`_ from ros-industrial/update_maintainers
  all: update maintainer and author information.
* all: update maintainer and author information.
* Merge branch 'kinetic-devel' into patch-1
* Add roslaunch tests (`#362 <https://github.com/davetcoleman/universal_robot/issues/362>`_)
  Squashed commits:
  * add roslaunch tests
  * add missed dependencies
  * Do not install roslaunch tests.
* Merge pull request `#342 <https://github.com/davetcoleman/universal_robot/issues/342>`_ from ipa-hsd/doc_attr
  Using the 'doc' attribute on 'arg' elements.
* Using the 'doc' attribute on 'arg' elements.
  add doc strings to all launch file args.
* 1.2.1
* update changelogs
* 1.2.0
* Update changelogs
* Merge pull request `#290 <https://github.com/davetcoleman/universal_robot/issues/290>`_ from ros-industrial/289_kinetic
  [kinetic] Remove dependency on ros_controllers metapackage.
* Remove dependency on ros_controllers metapackage.
  As per http://www.ros.org/reps/rep-0127.html, packages are not allowed to
  depend on metapackages.
* Merge pull request `#289 <https://github.com/davetcoleman/universal_robot/issues/289>`_ from tecnalia-advancedmanufacturing-robotics/remove_metapackage_dependency
  Remove dependency on ros_controllers metapackage.
* Remove dependency on ros_controllers metapackage.
  As per http://www.ros.org/reps/rep-0127.html, packages are not allowed to
  depend on metapackages.
* 1.1.9
* Update changelogs.
* 1.1.8
* Update changelogs.
* ur_gazebo: escape underscore in changelog. Fix `#279 <https://github.com/davetcoleman/universal_robot/issues/279>`_.
* all: update maintainers.
* 1.1.7
* Update changelogs.
* ur_gazebo: add controller_manager as run dependency.
  And remove gazebo_ros_pkgs, as it is a metapackage.
* Merge pull request `#237 <https://github.com/davetcoleman/universal_robot/issues/237>`_ from ros-industrial/indigo
  Updates from latest release
* Contributors: AndyZe, Dave Niewinski, Felix Mauch, Felix Messmer, G.A. vd. Hoorn, Hans-Joachim Krauch, Harsh Deshpande, Miguel Prada, Nadia Hammoudeh García, Qiang Qiu, gavanderhoorn, ipa-fxm

1.2.5 (2019-04-05)
------------------
* Update maintainer listing: add Miguel (`#410 <https://github.com/ros-industrial/universal_robot/issues/410>`_)
* UR-E Series (`#380 <https://github.com/ros-industrial/universal_robot/issues/380>`_)
* Update maintainer and author information.
* Add roslaunch tests (`#362 <https://github.com/ros-industrial/universal_robot/issues/362>`_)
* Using the 'doc' attribute on 'arg' elements.
* Contributors: Dave Niewinski, gavanderhoorn, Harsh Deshpande, Nadia Hammoudeh García

1.2.1 (2018-01-06)
------------------

1.2.0 (2017-08-04)
------------------
* Remove dependency on ros_controllers metapackage.
  As per http://www.ros.org/reps/rep-0127.html, packages are not allowed to
  depend on metapackages.
* Contributors: Miguel Prada

1.1.9 (2017-01-02)
------------------
* No changes.

1.1.8 (2016-12-30)
------------------
* ur_gazebo: escape underscore in changelog (`#279 <https://github.com/ros-industrial/universal_robot/issues/279>`_).
* all: update maintainers.
* Contributors: gavanderhoorn

1.1.7 (2016-12-29)
------------------
* ur_gazebo: add controller_manager as run dependency.
* Contributors: Hans-Joachim Krauch

1.1.6 (2016-04-01)
------------------
* provide launch files for ur3
* use controller_manager spawn
* allow to start gazebo without gui
* adjust controllers to new hardwareInterface - affects simulation only
* Contributors: ipa-fxm

1.0.2 (2014-03-31)
------------------

1.0.1 (2014-03-31)
------------------
* adapt launch files in order to be able to use normal/limited xacro
* updates for latest gazebo under hydro
* Contributors: ipa-fxm

* Added definitions for adding tergets in install folder. Issue `#10 <https://github.com/ros-industrial/universal_robot/issues/10>`_.
* Added definitions for adding tergets in install folder. Issue `#10 <https://github.com/ros-industrial/universal_robot/issues/10>`_.
* Updated to catkin.  ur_driver's files were added to nested Python directory for including in other packages.
* removed ``arm_`` prefix from joint names in gazebo controller config
* Renamed packages and new groovy version
* Added ur10 and renamed packages
* Contributors: IPR-SR2, Kelsey, Mathias Lüdtke, ipa-nhg, robot

1.0.0 (2014-03-31)
------------------
