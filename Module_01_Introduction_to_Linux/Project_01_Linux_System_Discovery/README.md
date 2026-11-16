Project 01: Linux System Discovery and Environment Report

1.  Project Overview

This project focuses on identifying and inspecting a linux operating system environment.

2. Scenario
I have joined an organization as aJunior Linux System Administrator.
My supervisor has assigned me a linux machine and requested an initial system assessment to establish the characteristics of the environment.
My responsibility is to inspect the system and document its configuration.

3.Project Objectives

  The objectives are to:

  1. Identify the installed Linux distribution.
  2. Determine the Ubuntu version
  3. Identify the linux kernel version
  4. Identify the current logged-in user.
  5. Determine the computer hostname.
  6. Identify the system architecture.
  7. Check the system uptime.
  8. Determine administration privileges.


4. Commands Used:

   lsb_release -a |Identify Linux Distribution
   uname -r       |Display kernel version
   uname -a       |DIsplay system information
   whoami         |Identify current user
   id             |Display user identity and groups
   hostname       |Display  computer hostname
   uname -m       |Identify system architecture
   uptime         |Display system uptime

5. Practical Implementation

 Commands were executed in an Ubuntu Linux terminal.
 The outputs were examined to identify the operating system characteristics and administrative access.

6. Project Deliverable
 
 linux_system_discovery_report.txt
 
 The report contains the actual findings obtained during system inspection.

7. Skills Demonstrated
  Linux environment identification
  Basic system auditing
  Linux command-line operations
  User and privilege identification
  System information gathering
  Technical documentation

8. Environment 
  Operating System: Ubuntu Linux
  Virtualization Platform: Oracle VirtualBox
  Project Type: Practical Linux Administration
 

