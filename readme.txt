Devel79 Tray � Jakub Trmota, 2012 (http://forrest79.net)


VirtualBox developer server tray icon.


HOW TO USE:
===========
devel79tray [--runserver|-r] [--config|-c filename]

Settings: --runserver, -r  run VirtualBox machine after application starts
          --config, -c     specify filename with configuration (default is "devel79.conf")

Configuration file:
name = Server name to display
machine = VirtualBox machine name (case sensitive)
ip = VirtualBox Network adapter IP address (used for ping command)

Tray icon menu:
Double click - if server is running show/hide VirtualBox console
Show console - if server is running show VirtualBox console
Hide console -if server is running hide VirtualBox console
Start server - if server is not running, start server
Restart server - if server is running, stop and start server
Stop server - if server is running, stop server
Ping server - if server is running, ping to server IP address a show result
Exit - exit tray icon, if server is running, show question for stop server or show VirtualBox console if is hidden


HISTORY
=======
1.0.0 [2010-01-01] - First public version in C#
2.0.0 [2012-05-07] - Rewritten using VirtualBox SDK, icons changed.
2.0.1 [2012-05-28] - Update to VirtualBoxSDK-4.1.16-78094.


REQUIREMENTS
============
You need .NET Framework 2 to run this application (http://www.microsoft.com/downloads/details.aspx?familyid=0856eacb-4362-4b0d-8edd-aab15c5e04f5&displaylang=en).


LICENSE
=======
Devel79 Tray is distributed under BSD license. See license.txt.


https://github.com/forrest79/devel79tray
