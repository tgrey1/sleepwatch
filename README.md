sleepwatch
==========

Usage:
$ sleepwatch wait_in_seconds [ lockfile ]

This is a simple timer / sleep wrapper that uses a lockfile for triggering.  Use it in place of sleep when you want to be able to force the timer to reset.  A reset can be triggered by removing the lockfile, which is set at runtime as an option.

WARNING: lockfile will be overwritten/deleted without a prompt!  Use caution providing input.

----------

This script has primarily been tested in OSX 10.7.5 with Bash version 3.2.48(1)-release, but it should be portable enough to work just about anywhere.

If reporting an issue, please include your operating system version and bash version in the report.
