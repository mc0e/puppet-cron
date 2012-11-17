# vim: set ft=ruby ts=2 sts=2 sw=2 et:

name    'torrancew-cron'
author  'Tray Torrance'
version '0.1.0'
license 'Apache License 2.0'

summary     'A puppet module for managing cron jobs via cron.d'
description 'This module provides defined types for the following:
  cron::hourly  - A configurable hourly cron.d job file
  cron::daily   - A configurable daily cron.d job file
  cron::weekly  - A configurable weekly cron.d job file
  cron::monthly - A configurable monthly cron.d job fil
  cron::job     - A configurable generic cron.d job file
  
  All jobs allow configuration of the following parameters:
    environment - An array or newline-separated string of environment variables
    user        - The user the job should be executed as
    command     - The command to execute

  Additionally, each type of job allows configuration of the corresponding
  relevant cron time fields:
    cron::hourly  - minute
    cron::daily   - minute, hour
    cron::weekly  - minute, hour, weekday
    cron::monthly - minute, hour, date
    cron::job     - minute, hour, date, month, weekday
'  

project_page 'https://github.com/torrancew/puppet-cron'
source       'https://github.com/torrancew/puppet-cron'

