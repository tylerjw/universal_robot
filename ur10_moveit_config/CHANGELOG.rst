^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package ur10_moveit_config
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.2.8 (2020-10-28)
------------------
* Fix MoveIt API change error for attempts
  Fixes 'Kinematics solver doesn't support #attempts anymore, but only a timeout.'
* Merge remote-tracking branch 'origin/melodic-devel' into calibration_devel
* migrated all package.xml files to format=2 (`#439 <https://github.com/davetcoleman/universal_robot/issues/439>`_)
* 1.2.5
* Update changelogs. (`#418 <https://github.com/davetcoleman/universal_robot/issues/418>`_)
* Update maintainer listing: add Miguel (`#410 <https://github.com/davetcoleman/universal_robot/issues/410>`_)
  * Add Migual Prada as maintainer.
  * Sort maintainers alphabetically.
  * Fix maintainers and author listing in all e-series pkgs.
  Was missing from `#380 <https://github.com/davetcoleman/universal_robot/issues/380>`_.
* MoveGroupExecuteService is Deprecated by MoveIt! (`#391 <https://github.com/davetcoleman/universal_robot/issues/391>`_)
  Squashed commits:
  * Deprecated Item
  replace MoveGroupExecuteService with MoveGroupExecuteTrajectoryAction
  * Deprecated item
  * Deprecated item
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
* 1.2.1
* update changelogs
* Reduce longest valid segment fraction to accomodate non-limited version of the UR5 (`#266 <https://github.com/davetcoleman/universal_robot/issues/266>`_)
* 1.2.0
* Update changelogs
* Merge pull request `#309 <https://github.com/davetcoleman/universal_robot/issues/309>`_ from ros-industrial/indigo-devel
  [kinetic] indigo devel updates
* Merge pull request `#285 <https://github.com/davetcoleman/universal_robot/issues/285>`_ from davetcoleman/fix_moveit_warning
  Fix Deprecated warning in MoveIt: parameter moved into namespace
* Fix Deprecated warning in MoveIt: parameter moved into namespace 'trajectory_execution'
* 1.1.9
* Update changelogs.
* moveit_config: use '--inorder' for jade+ xacro as well.
* moveit_config: make RViz load MoveIt display by default.
* 1.1.8
* Update changelogs.
* all: update maintainers.
* 1.1.7
* Update changelogs.
* Don't depend on moveit_plugins metapackage
  Instead, depend on the individual plugin packages needed.
* Merge pull request `#251 <https://github.com/davetcoleman/universal_robot/issues/251>`_ from davetcoleman/indigo-devel-xacro-fixes
  Fix xacro warnings in Jade
* Fix xacro warnings in Jade
* Merge pull request `#237 <https://github.com/davetcoleman/universal_robot/issues/237>`_ from ros-industrial/indigo
  Updates from latest release
* Contributors: Dave Coleman, Felix Mauch, Felix Messmer, G.A. vd. Hoorn, Jon Binney, Nadia Hammoudeh García, Qiang Qiu, Scott Paulin, Shaun Edwards, gavanderhoorn, ipa-fxm, 薯片半价

1.2.5 (2019-04-05)
------------------
* Update maintainer listing: add Miguel (`#410 <https://github.com/ros-industrial/universal_robot/issues/410>`_)
* MoveGroupExecuteService is Deprecated by MoveIt! (`#391 <https://github.com/ros-industrial/universal_robot/issues/391>`_)
* Update maintainer and author information.
* Add roslaunch tests (`#362 <https://github.com/ros-industrial/universal_robot/issues/362>`_)
* Contributors: gavanderhoorn, Nadia Hammoudeh García, 薯片半价

1.2.1 (2018-01-06)
------------------
* Reduce longest valid segment fraction to accomodate non-limited version of the UR5 (`#266 <https://github.com//ros-industrial/universal_robot/issues/266>`_)
* Contributors: Scott Paulin

1.2.0 (2017-08-04)
------------------
* Fix Deprecated warning in MoveIt: parameter moved into namespace 'trajectory_execution'
* Contributors: Dave Coleman

1.1.9 (2017-01-02)
------------------
* use '--inorder' for jade+ xacro as well.
* make RViz load MoveIt display by default.
* Contributors: gavanderhoorn

1.1.8 (2016-12-30)
------------------
* all: update maintainers.
* Contributors: gavanderhoorn

1.1.7 (2016-12-29)
------------------
* Don't depend on moveit_plugins metapackage
* Fix xacro warnings in Jade
* Contributors: Dave Coleman, Jon Binney

1.1.6 (2016-04-01)
------------------
* add missing dependency for moveit_simple_controller_manager
* Merge branch 'indigo-devel' of github.com:ros-industrial/universal_robot into ur3_moveit_config
* apply latest setup assistant changes to ur5 and ur10
* Adding comment explaining the choice of default planning algorithm
* Use RRTConnect by default for UR10
  Fixes bug `#193 <https://github.com/ros-industrial/universal_robot/issues/193>`_ about slow planning on Indigo
  LBKPIECE1 (the previous default) looks to be the wrong planning algorithm for the robot
  See https://groups.google.com/forum/#!topic/moveit-users/M71T-GaUNgg
* crop ik solutions wrt joint_limits
* set planning time to 0
* reduce planning attempts in moveit rviz plugin
* Contributors: Marco Esposito, ipa-fxm

1.0.2 (2014-03-31)
------------------

1.0.1 (2014-03-31)
------------------
* changes due to file renaming
* update moveit_configs: include ee_link and handle limited robot
* new moveit_configs for ur5 and ur10
* Contributors: ipa-fxm

1.0.0 (2014-03-31)
------------------
