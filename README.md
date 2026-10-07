# Fundamental Friday: Log Analysis Lab

These are copies of two log files from a fictional company's web server, gms-web01, which belongs to Gulfside Marine Supply.

* access.log is the Apache web server log. Every line is a request someone made to the website.
* auth.log is the Linux authentication log. It records logins, failed logins, sudo use, and account changes.

The logs cover October 8, 2026 at 6:00 AM through October 9, 2026 at 8:30 AM, Eastern time.

## Check your copy

Run these from inside this folder. Your numbers must match these before the session starts.

    wc -l access.log auth.log

You should see 3014 lines for access.log and 590 lines for auth.log.

## Rules

All IP addresses in these files come from ranges reserved for documentation, so none of them belong to a real person or company. Do not scan or contact any of them.

Do not edit these files. If you break one, run git checkout on it to get the original back.
