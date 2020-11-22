# About

SMS Sync handle request from SMSSync app and treat valid request as incoming SMS.

This way Android phones can be enabled as SMS modem/receiver for playSMS.

SMSSync app for Android can be found here:
http://smssync.ushahidi.com/download/

Info          | Data
--------------|-----------------------------------------
Author        | [Anton Raharja](http://antonraharja.com)
Created       | 131119
Last update   | 201122
Version       | 1.1
Compatibility | playSMS 1.1 and above
License       | GPLv3

# Changelog

Version 1.1
- always use secret
- some enhancements

Version 1.0
- changelog started

# Installation

Current version of this plugin should work with playSMS 1.1 and above.

Here is how to install it on a working playSMS:

1. Stop `playsmsd`, just make sure to stop it
2. Copy `web/plugin/feature/sms_sync` to the playSMS `plugin/feature` folder
3. Re-start `playsmsd`
4. Login to web with admin accounts and visit **Features -> Manage SMS sync**
