^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package ur5_e_moveit_config
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

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
* UR-E Series (`#380 <https://github.com/davetcoleman/universal_robot/issues/380>`_)
  * Added meshes for E series as well as gazebo and descriptions
  * Added example MoveIt! configs for the E-series arms
  * updated default planner for moveit config
  * Updated metapackage
  * Updated urE ambiance so gazebo looks right
  * e_description: add proper collision models.
  Simple convex hulls for now, but these could be replaced with more
  advanced convex decompositions in later PRs.
* Contributors: Dave Coleman, Dave Niewinski, Felix Mauch, G.A. vd. Hoorn, gavanderhoorn

1.2.5 (2019-04-05)
------------------
* First release (of this package)
* Update maintainer listing: add Miguel (`#410 <https://github.com/ros-industrial/universal_robot/issues/410>`_)
* UR-E Series (`#380 <https://github.com/ros-industrial/universal_robot/issues/380>`_)
* Contributors: Dave Niewinski, gavanderhoorn

1.0.0 (2014-03-31)
------------------
