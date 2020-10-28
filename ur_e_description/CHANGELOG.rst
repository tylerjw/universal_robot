^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package ur_e_description
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.2.8 (2020-10-28)
------------------
* Fix test errors by adding config files to install
* Merge remote-tracking branch 'origin/melodic-devel' into calibration_devel
* Merge pull request `#437 <https://github.com/davetcoleman/universal_robot/issues/437>`_ from ipa-nhg/safetylimits
  Add optional safety_controller tags to all joints in xacro macros
* migrated all package.xml files to format=2 (`#439 <https://github.com/davetcoleman/universal_robot/issues/439>`_)
* Add optional safety_controller tags for e series descriptions
* Merge pull request `#426 <https://github.com/davetcoleman/universal_robot/issues/426>`_ from fmauch/inertia
  corrected dimensions and positions of inertias
* Merge pull request `#435 <https://github.com/davetcoleman/universal_robot/issues/435>`_ from fmauch/add_description_view_files
  Add description view files
* Add dependencies for view_x.launch files to the description packages
  As we use the joint_state_publisher, the robot_state_publisher and rviz
  inside the launch files, I added them as run-dependencies.
* Added view_x.launch files for all descriptions to easily check them.
  This resolves `#432 <https://github.com/davetcoleman/universal_robot/issues/432>`_
  To avoid introducing another dependency, I copied the rviz configuration
  from industrial_robot_client.
* fixed rotation axis of wrist_1 in UR3e and UR5e
* Use correct ee_link orientation for eSeries
* formatting correction for ur10e xacro
* fix: load correct parameter set for ur10e
* added ur3e and ur5e
* added hash string to default paramset for ur10e and ur10
* use calibration in ur10e
* corrected dimensions and positions of inertias
  I'm by far not an expert in working with gazebo or inertias, but it seemed wrong to me:
  - The upper arm inertia of the ur10 is not centered in the visual arm segment
  - CoM in the wrist links don't sit inside the correct links. E.g. wrist1 has its CoM inside the end of the forearm for all robots.
  - Because of the second point the inertia's geometry of wrist3 is matching wrist2 instead of the actual moving part of wrist3.
  - Wrist dimensions of ur5 were completely off.
  - On the ur5e the arm inertias weren't centered in the visuals.
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
* Contributors: Alex Tyshka, Dave Niewinski, Felix Mauch, G.A. vd. Hoorn, JeremyZoss, gavanderhoorn, ipa-nhg

1.2.5 (2019-04-05)
------------------
* First release (of this package)
* Update maintainer listing: add Miguel (`#410 <https://github.com/ros-industrial/universal_robot/issues/410>`_)
* UR-E Series (`#380 <https://github.com/ros-industrial/universal_robot/issues/380>`_)
* Contributors: Dave Niewinski, gavanderhoorn

1.0.0 (2014-03-31)
------------------
