## 2025-11-01
* Bump for oxiscripts to handle rsync jobs for document backup

## 2025-10-25
* Bump for syslogrole to support check mode

## 2025-10-11
* Bump for apt sources updates

## 2025-10-10
* Add new role to silence prometheus alert manager on systemd timers (systemd_am_silence)

## 2025-10-05
* Lookup user homes instead of guesstimating

## 2025-10-04
* Ensure switch variable is bool

## 2025-10-03
* Support Trixie on Raspberry pis for apt_source

## 2025-09-27
* Bump for oxiscripts role install improvement

## 2025-09-08
* Bump for nextcloud_davfs role

## 2025-08-29
* Bump for nextcloud_davfs role

## 2025-08-15
* Bump for apt_source to add linux mint zara (22.2) support

## 2025-08-14
* Bump for apt_source to add debian trixie support for x86

## 2025-05-29
* Bump for nextcloud_davfs bugfix

## 2025-05-14
* Bump nextcloud_davfs to support and default to mount the Nextcloud folder also as user

## 2025-05-08
* Bump for smartd bugfix
* Bump for apt_source (adding linux mint xia) and use HTTPS per default
* Bump for deploy_user now supporting min and max UID

## 2025-03-17
* Bump for oxiscripts role bugfix

## 2025-02-23
* Bump for apt_source role bugfix

## 2025-02-17
* Bump for oxiscripts role bugfix

## 2025-02-14
* Bump for oxiscripts role. Please see the role for details, this will break stuff if you use rsync or documents backup jobs!

## 2025-02-08
* Bump for all roles to remove unused tests directory to make linter happy
* Fix several variable names where the linter was not happy
* Removed old ntp role from collection
* Everything is now correctly linted

## 2024-10-17
* Bump for oxiscripts role

## 2024-09-29
* Add kernel_module role

## 2024-09-18
* Bump for packages role. Be aware, this is a braking change for variable name.

## 2024-09-08
* Bump for rsyslog role

## 2024-09-05
* Add grub_cmdline_options role

## 2024-09-03
* Bump for role rebootcheck

## 2024-08-24
* Bump nextcloud_davfs for improved cron job

## 2024-08-12
* Bump oxiscripts role to support backup cleanup days

## 2024-07-10
* Support deploy_user_groupname in deploy_user role

## 2024-06-28
* Adding pipeline badge
* Adding supported minimal version for linter
* Improve readme

## 2024-05-24
* Support noble in apt_source role

## 2024-05-07
* Rewrite ssh server role:
  * Add readme
  * Remove legacy raspberry tasks
  * No longer hardcoded settings, they are defaults now

## 2024-05-01
* Nextcloud DAVFS role: Make cache size configurable
