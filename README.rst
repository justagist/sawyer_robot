Added force torque sensor to gazebo simulation (in branch release-5.2.0). Requires sawyer_description repo (https://github.com/justagist/sawyer_robot) and intera_common (https://github.com/RethinkRobotics/intera_common) of the same branch.


Sawyer Robot
==============

The Sawyer Robot is a platform for development of custom automation applications using the Intera SDK.

This repository contains metapackages and files for installation/use of the Sawyer Robot.

Installation
------------
| Please follow the Getting Started wiki page for instructions on installation of the Intera SDK:
| http://sdk.rethinkrobotics.com/intera/Workstation_Setup

Code & Tickets
--------------

+-----------------+------------------------------------------------------------------------------+
| Documentation   | http://sdk.rethinkrobotics.com/intera/                                       |
+-----------------+------------------------------------------------------------------------------+
| Issues          | https://github.com/RethinkRobotics/sawyer_robot/issues                       |
+-----------------+------------------------------------------------------------------------------+
| Contributions   | https://github.com/RethinkRobotics/sawyer_robot/blob/master/CONTRIBUTING.md  |
+-----------------+------------------------------------------------------------------------------+

Sawyer Repository Overview
--------------------------

::

     .
     |
     +-- sawyer_robot/             sawyer robot metapackage containing all sawyer-specific packages
     |
     +-- sawyer_robot.rosinstall   rosinstall script containing all required sawyer dependency repos
     |
     +-- sawyer_description/       urdf and meshes describing sawyer


Other Sawyer Repositories
-------------------------
+------------------+-----------------------------------------------------+
| intera_sdk       | https://github.com/RethinkRobotics/intera_sdk       |
+------------------+-----------------------------------------------------+
| intera_commom    | https://github.com/RethinkRobotics/intera_common    |
+------------------+-----------------------------------------------------+
| sawyer_moveit    | https://github.com/RethinkRobotics/sawyer_moveit    |
+------------------+-----------------------------------------------------+

Latest Release Information
--------------------------

http://sdk.rethinkrobotics.com/intera/Release-Changes
