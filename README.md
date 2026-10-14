# Toggl → Jira releases

Installers for the Toggl → Jira desktop app (Windows). The source lives in a separate,
private repository; this one holds only releases.

**To install:** download the latest `Toggl-Jira_*_x64-setup.exe` from
[Releases](../../releases/latest) and run it. It installs for your user only and needs no
admin rights. Windows SmartScreen may warn the first time because the installer is not
code-signed with a purchased certificate.

**Updates** after that are automatic: the app checks this repository's latest release and
offers an Update button in its sidebar. Every installer is signed, and the app refuses one
whose signature does not match its built-in key.
