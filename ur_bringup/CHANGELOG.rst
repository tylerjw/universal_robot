^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package ur_bringup
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

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
* Merge pull request `#322 <https://github.com/davetcoleman/universal_robot/issues/322>`_ from gavanderhoorn/use_robot_state_publisher
  driver: don't use deprecated robot_state binary.
* driver: don't use deprecated robot_state binary.
* 1.2.0
* Update changelogs
* 1.1.9
* Update changelogs.
* 1.1.8
* Update changelogs.
* all: update maintainers.
* 1.1.7
* Update changelogs.
* Merge pull request `#253 <https://github.com/davetcoleman/universal_robot/issues/253>`_ from Jntzko/prefixInLaunch
  Add prefix parameter in common launch
* Add prefix parameter in common launch
  We want to set a prefix when starting the ur_common.launch, so we add
  the prefix argument and set the parameter for the driver.
* Merge pull request `#237 <https://github.com/davetcoleman/universal_robot/issues/237>`_ from ros-industrial/indigo
  Updates from latest release
* Contributors: Felix Mauch, Felix Messmer, G.A. vd. Hoorn, Harsh Deshpande, Nadia Hammoudeh García, Qiang Qiu, Thomas Timm Andersen, Yannick Jonetzko, gavanderhoorn, ipa-fxm

1.2.5 (2019-04-05)
------------------
* Update maintainer listing: add Miguel (`#410 <https://github.com/ros-industrial/universal_robot/issues/410>`_)
* update maintainer and author information.
* Add roslaunch tests (`#362 <https://github.com/ros-industrial/universal_robot/issues/362>`_)
* Using the 'doc' attribute on 'arg' elements.
* Contributors: gavanderhoorn, Harsh Deshpande, Nadia Hammoudeh García

1.2.1 (2018-01-06)
------------------
* Merge pull request `#322 <https://github.com//ros-industrial/universal_robot/issues/322>`_ from gavanderhoorn/use_robot_state_publisher
  driver: don't use deprecated robot_state binary.
* driver: don't use deprecated robot_state binary.
* Contributors: Felix Messmer, gavanderhoorn

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
* Add prefix parameter in common launch
* Contributors: Yannick Jonetzko

1.1.6 (2016-04-01)
------------------
* provide launch files for ur3
* Contributors: ipa-fxm

1.0.2 (2014-03-31)
------------------

1.0.1 (2014-03-31)
------------------
* adapt launch files in order to be able to use normal/limited xacro
* Contributors: ipa-fxm

* Added definitions for adding tergets in install folder. Issue `#10 <https://github.com/ros-industrial/universal_robot/issues/10>`_.
* Added definitions for adding tergets in install folder. Issue `#10 <https://github.com/ros-industrial/universal_robot/issues/10>`_.
* Updated to catkin.  ur_driver's files were added to nested Python directory for including in other packages.
* Updated urdf files use collision/visual models.
* Added launch directory to bringup package.  Left the old launch files to be backwards compatable for now.  Updated driver with SwRI internal changes.  Changed driver to accept ip address to match ROS-Industrial standard.  IP addresses for industrial robots are typically fixed.  Hostnames are not typically used (this is what the driver expected)
* Removed extra stl files and fixed indentions
* Renamed packages and new groovy version
* Added ur10 and renamed packages
* Contributors: IPR-SR2, Kelsey, Shaun Edwards, ipa-nhg, robot

1.0.0 (2014-03-31)
------------------
