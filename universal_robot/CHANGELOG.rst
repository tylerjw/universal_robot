^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package universal_robot
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.2.8 (2020-10-28)
------------------
* Merge remote-tracking branch 'origin/melodic-devel' into calibration_devel
* migrated all package.xml files to format=2 (`#439 <https://github.com/davetcoleman/universal_robot/issues/439>`_)
* 1.2.5
* Update changelogs. (`#418 <https://github.com/davetcoleman/universal_robot/issues/418>`_)
* Update maintainer listing: add Miguel (`#410 <https://github.com/davetcoleman/universal_robot/issues/410>`_)
  * Add Migual Prada as maintainer.
  * Sort maintainers alphabetically.
  * Fix maintainers and author listing in all e-series pkgs.
  Was missing from `#380 <https://github.com/davetcoleman/universal_robot/issues/380>`_.
* add new metapackage, first step to rename the repo (`#409 <https://github.com/davetcoleman/universal_robot/issues/409>`_)
  * add new metapackage, first step to rename the repo
  * meta: use package format 2.
  * meta: depend on all UR packages.
  * Make old metapkg depend on new one.
  Transitional period only.
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
* 1.2.1
* update changelogs
* 1.2.0
* Update changelogs
* 1.1.9
* Update changelogs.
* 1.1.8
* Update changelogs.
* all: update maintainers.
* 1.1.7
* Update changelogs.
* Merge pull request `#237 <https://github.com/davetcoleman/universal_robot/issues/237>`_ from ros-industrial/indigo
  Updates from latest release
* Contributors: Dave Niewinski, Felix Mauch, Felix Messmer, G.A. vd. Hoorn, Nadia Hammoudeh García, gavanderhoorn, ipa-fxm

1.2.5 (2019-04-05)
------------------
* Update maintainer listing: add Miguel (`#410 <https://github.com/ros-industrial/universal_robot/issues/410>`_)
* Add new metapackage, first step to rename the repo (`#409 <https://github.com/ros-industrial/universal_robot/issues/409>`_)
* UR-E Series (`#380 <https://github.com/ros-industrial/universal_robot/issues/380>`_)
* Update maintainer and author information.
* Contributors: Dave Niewinski, Nadia Hammoudeh García, gavanderhoorn

1.2.1 (2018-01-06)
------------------

1.2.0 (2017-08-04)
------------------

1.1.9 (2017-01-02)
------------------
* No changes.

1.1.8 (2016-12-30)
------------------
* all: update maintainers.
* Contributors: gavanderhoorn

1.1.7 (2016-12-29)
------------------
* No changes.

1.1.6 (2016-04-01)
------------------
* add moveit_config for ur3
* Contributors: ipa-fxm

1.0.2 (2014-03-31)
------------------
* Merge branch 'hydro-devel' of github.com:ros-industrial/universal_robot into hydro
* added missing dependency
* Contributors: Florian Weisshardt, ipa-fxm

1.0.1 (2014-03-31)
------------------

* Added all packages in dependency list of metapackage.
* Updated to catkin.  ur_driver's files were added to nested Python directory for including in other packages.
* Contributors: IPR-SR2, Kelsey

1.0.0 (2014-03-31)
------------------
