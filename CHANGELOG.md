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
