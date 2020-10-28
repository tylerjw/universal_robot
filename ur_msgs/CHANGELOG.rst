^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package ur_msgs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.2.8 (2020-10-28)
------------------
* Merge remote-tracking branch 'origin/melodic-devel' into calibration_devel
* Added a service to set the speed slider position (`#454 <https://github.com/davetcoleman/universal_robot/issues/454>`_)
  Squashed commits:
  * Added a service to set the speed slider position
  * Use a more specific name for the data
  The name used is the same as defined in the RTDE interface.
  * Added an explanation with valid data range to the service.
  * Update comment.
  * Renamed service to SetSpeedSliderFraction
  This better represents the technical background
  * Use correct name of svc def file.
  * Fixup
* Added a domain field to Analog.msg (`#450 <https://github.com/davetcoleman/universal_robot/issues/450>`_)
  On UR robots the domain of analog in- and outputs can be configured.
  The Analog.msg didn't cover this so far.
* migrated all package.xml files to format=2 (`#439 <https://github.com/davetcoleman/universal_robot/issues/439>`_)
* 1.2.5
* Update changelogs. (`#418 <https://github.com/davetcoleman/universal_robot/issues/418>`_)
* msgs: correct width and type of 'digital\_*_bits'. (`#416 <https://github.com/davetcoleman/universal_robot/issues/416>`_)
* msgs: clarify use of fields in SetIO svc. (`#415 <https://github.com/davetcoleman/universal_robot/issues/415>`_)
* Update maintainer listing: add Miguel (`#410 <https://github.com/davetcoleman/universal_robot/issues/410>`_)
  * Add Migual Prada as maintainer.
  * Sort maintainers alphabetically.
  * Fix maintainers and author listing in all e-series pkgs.
  Was missing from `#380 <https://github.com/davetcoleman/universal_robot/issues/380>`_.
* Add RobotModeDataMsg (`#395 <https://github.com/davetcoleman/universal_robot/issues/395>`_)
  * Add RobotModeDataMsg
  * msg: clarify that not all fields from RobotMode are published
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
* Add message definition for ToolData.
* Merge pull request `#237 <https://github.com/davetcoleman/universal_robot/issues/237>`_ from ros-industrial/indigo
  Updates from latest release
* Contributors: Felix Mauch, Felix Messmer, Felix von Drigalski, G.A. vd. Hoorn, Nadia Hammoudeh García, Nikolas Engelhard, gavanderhoorn, ipa-fxm

1.2.5 (2019-04-05)
------------------
* Correct width and type of 'digital\_*_bits'. (`#416 <https://github.com/ros-industrial/universal_robot/issues/416>`_)
* Clarify use of fields in SetIO svc. (`#415 <https://github.com/ros-industrial/universal_robot/issues/415>`_)
* Update maintainer listing: add Miguel (`#410 <https://github.com/ros-industrial/universal_robot/issues/410>`_)
* Add RobotModeDataMsg (`#395 <https://github.com/ros-industrial/universal_robot/issues/395>`_)
* Update maintainer and author information.
* Contributors: Felix von Drigalski, gavanderhoorn

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
* Add message definition for ToolData.
* Contributors: Nikolas Engelhard

1.1.6 (2016-04-01)
------------------
* Moved SetIO FUN constants from driver.py to relevant srv file for easier interaction from other files
* catkin_lint
* Contributors: Thomas Timm Andersen, ipa-fxm

1.0.0 (2014-03-31)
------------------
