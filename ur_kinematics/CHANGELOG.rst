^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package ur_kinematics
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.2.8 (2020-10-28)
------------------
* Replace joint_model_group with joint_model_group\_
* Upgrade KinematicsBase API and ClassLoader usage to Melodic
* Remove whitespace
* Merge remote-tracking branch 'origin/melodic-devel' into calibration_devel
* Merge pull request `#372 <https://github.com/davetcoleman/universal_robot/issues/372>`_ from qqfly/patch-1
  simplify FK equations
* migrated all package.xml files to format=2 (`#439 <https://github.com/davetcoleman/universal_robot/issues/439>`_)
* 1.2.5
* Update changelogs. (`#418 <https://github.com/davetcoleman/universal_robot/issues/418>`_)
* Update maintainer listing: add Miguel (`#410 <https://github.com/davetcoleman/universal_robot/issues/410>`_)
  * Add Migual Prada as maintainer.
  * Sort maintainers alphabetically.
  * Fix maintainers and author listing in all e-series pkgs.
  Was missing from `#380 <https://github.com/davetcoleman/universal_robot/issues/380>`_.
* Merge pull request `#404 <https://github.com/davetcoleman/universal_robot/issues/404>`_ from jwhendy/kdl-includes
  removed non-existent moveit KDL libraries from ur_kinematics includes
* removed non-existent moveit KDL libraries from ur_kinematics includes
* Merge branch 'kinetic-devel' into mesh-brightness
* Merge pull request `#387 <https://github.com/davetcoleman/universal_robot/issues/387>`_ from ros-industrial/update_maintainers
  all: update maintainer and author information.
* all: update maintainer and author information.
* Merge branch 'kinetic-devel' into patch-1
* Missed python module definition and setup.py script (`#364 <https://github.com/davetcoleman/universal_robot/issues/364>`_)
  Merged commits:
  * missed python module definition and setup.py script
  * clean the __init_\_ file
* Use the new proposed API to query params from correct namespaces (`#334 <https://github.com/davetcoleman/universal_robot/issues/334>`_)
* setting default ik_weights to 1.0 (`#346 <https://github.com/davetcoleman/universal_robot/issues/346>`_)
* simplify FK equations
* Merge branch 'kinetic-devel' into doc_attr
* Merge branch 'kinetic-devel' into add_support_level_badge
* Merge branch 'kinetic-devel' into fixMeshes
* Merge branch 'kinetic-devel' into gazebo_tag_selfCollide
* Merge pull request `#338 <https://github.com/davetcoleman/universal_robot/issues/338>`_ from machinekoder/kinetic-devel
  ur_moveit_plugin: fix compile error with GCC6
* ur_moveit_plugin: fix compile error with GCC6
* 1.2.1
* update changelogs
* Merge pull request `#303 <https://github.com/davetcoleman/universal_robot/issues/303>`_ from marcoesposito1988/pr-urdf-pointer-type
  Updated urdf::ModelInterface pointer type for ROS Lunar
* 1.2.0
* Update changelogs
* Updated urdf::ModelInterface pointer type for ROS Lunar
* Merge pull request `#286 <https://github.com/davetcoleman/universal_robot/issues/286>`_ from davetcoleman/kinetic-fix
  Fixup for MoveIt! Kinetic
* Fixup for MoveIt! Kinetic
* 1.1.9
* Update changelogs.
* 1.1.8
* Update changelogs.
* all: update maintainers.
* 1.1.7
* Update changelogs.
* Merge pull request `#275 <https://github.com/davetcoleman/universal_robot/issues/275>`_ from 130s/fix/274
  Depend on new moveit_kinematics pkg now that MoveIt has moved the kinematics plugins.
* Fix `#274 <https://github.com/davetcoleman/universal_robot/issues/274>`_
* Merge pull request `#237 <https://github.com/davetcoleman/universal_robot/issues/237>`_ from ros-industrial/indigo
  Updates from latest release
* Contributors: Alexander Rössler, Dave Coleman, Felix Mauch, Felix Messmer, G.A. vd. Hoorn, Henning Kayser, Isaac I.Y. Saito, Levi Armstrong, Marco Esposito, Miguel Prada, Mike Lautman, Nadia Hammoudeh García, Qiang Qiu, Shaun Edwards, gavanderhoorn, ipa-fxm, jwhendy

1.2.5 (2019-04-05)
------------------
* Update maintainer listing: add Miguel (`#410 <https://github.com/ros-industrial/universal_robot/issues/410>`_)
* Removed non-existent moveit KDL libraries from ur_kinematics includes
* Update maintainer and author information.
* Missed python module definition and setup.py script (`#364 <https://github.com/ros-industrial/universal_robot/issues/364>`_)
* Use the new proposed API to query params from correct namespaces (`#334 <https://github.com/ros-industrial/universal_robot/issues/334>`_)
* Setting default ik_weights to 1.0 (`#346 <https://github.com/ros-industrial/universal_robot/issues/346>`_)
* ur_moveit_plugin: fix compile error with GCC6
* Contributors: Alexander Rössler, gavanderhoorn, Henning Kayser, Mike Lautman, Nadia Hammoudeh García, jwhendy

1.2.1 (2018-01-06)
------------------
* Merge pull request `#303 <https://github.com//ros-industrial/universal_robot/issues/303>`_ from marcoesposito1988/pr-urdf-pointer-type
  Updated urdf::ModelInterface pointer type for ROS Lunar
* Updated urdf::ModelInterface pointer type for ROS Lunar
* Contributors: G.A. vd. Hoorn, Marco Esposito

1.2.0 (2017-08-04)
------------------
* Fixup for MoveIt! Kinetic
* Contributors: Dave Coleman

1.1.9 (2017-01-02)
------------------
* No changes.

1.1.8 (2016-12-30)
------------------
* all: update maintainers.
* Contributors: gavanderhoorn

1.1.7 (2016-12-29)
------------------
* Depend on new moveit_kinematics package (`#274 <https://github.com/ros-industrial/universal_robot/issues/274>`_).
* Contributors: Isaac I.Y. Saito

1.1.6 (2016-04-01)
------------------
* apply ur-kin-constants fix for ur3
* Merge remote-tracking branch 'origin-rosi/indigo-devel' into ur-kin-constants
* ur_kinematics: Move #defines to constants in source file.
* ur_kinematics for ur3
* crop ik solutions wrt joint_limits
* Contributors: Maarten de Vries, ipa-fxm

1.0.2 (2014-03-31)
------------------

1.0.1 (2014-03-31)
------------------

* Added definitions for adding tergets in install folder. Issue `#10 <https://github.com/ros-industrial/universal_robot/issues/10>`_.
* Added definitions for adding tergets in install folder. Issue `#10 <https://github.com/ros-industrial/universal_robot/issues/10>`_.
* Updated to catkin.  ur_driver's files were added to nested Python directory for including in other packages.
* added IKfast compatibility functions
* Ported ur_kinematics package from Georgia Tech library.  Added ability to create ur5 & ur10 kinematics libraries.  Python libaries not untested.  Kinematics still needs to be wrapped within Kinematics plugin interface
* Contributors: IPR-SR2, Kelsey, Mathias Lüdtke, Shaun Edwards

1.0.0 (2014-03-31)
------------------
