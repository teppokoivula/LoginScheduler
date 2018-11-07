# Login Scheduler for ProcessWire CMS/CMF

Login Scheduler adds a couple of new fields to user template(s) and provides
support for disabling login for non-superuser accounts either instantly with
a checkbox ("Login disabled"), or by specifying a time range ("Login allowed
starting from" or "Login allowed until").

If a user is already logged in when login access is disabled, logout should
be triggered during next session validity check (usually next page load).