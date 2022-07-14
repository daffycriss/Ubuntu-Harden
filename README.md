# Ubuntu-Harden
Hardening Script for Ubuntu 20.04

All scripts are based on CIS Ubuntu Hardening Benchmark.
============================================================================================================================

!!! IMPORTANT !!!

This Guide is Referred to a Clean Installation of Ubuntu Desktop 20.04.

Most of the Scripts Also Work on Server Version, as well as on Previous Ubuntu Versions.

However, the Documentation Should be Read Carefully Before Running the Script Because Many Services Will be
Disabled and/or Removed.

If you don't Want Some of these Services to b Disabled you Need to Remove them From the Script or
Comment the Appropriate Lines.

Additionally, Hardening a System is not a Static Procedure but an Every Day Task.

More Tasks are Need to be Done (for example: masking services, or port blocking).

passfile & unfile
============================================================================================================================
Files created in order to support the functionality of Script: 2.SecureBootSettings


newmessagefile
============================================================================================================================
File created in order to support the functionality of Script: 7.GnomeDisplayManager

IPv6
============================================================================================================================
Additional Attention Should be Taken to Proper Configuration of SSH X11forwarding.
Details are Included in the Script
