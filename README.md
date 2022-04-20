# Logwatcher

This is a bash script that can be set up in cron and pointed at a directory to look for specific errors or patterns in a time frame and send notifications.

# Requirements

- mutt for sending email
- standard linux toolset: sed, date, head, egrep, cut, cat, and wc

# Usage

1. Update `LOGDIR` to point to your log directory
2. Update `LOGEXT` with the extension of files to look for
3. Update paths to tools needed for script (lines 8-15)
4. If necessary change your time frame on line 20
5. Update patterns to look for in regular expression on lin 38
6. Set up cron job to run the script at necessary interval.
