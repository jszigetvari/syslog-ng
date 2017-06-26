# syslog-ng

(Please, remove the unnecessary notes, including this one.)

## Version of syslog-ng

```
output of syslog-ng --version
```

## Platform

(Name and version of OS)

## Debug bundle

Create a debug bundle on your system with the syslog-debun script which is included in the syslog-ng package.

Overwiew of the CLI options of syslog-debun:
-r: run actual information gathering
-d: run syslog-ng in debug mode
-p: perform packet capture
-s: do strace
-t: timeout period for running debug/pcap/strace
-w: wait period before starting debug mode
-l: light information gathering (respects privacy)
-R: alternate installation directory for syslog-ng

```
$ syslog-debun
```

# Issue

## Failure

(Backtrace, error messages or detailed description of failure comes here.)
(To create debug bundles, use `syslog-debun`. Details of its usage can be found [here](https://www.balabit.com/sites/default/files/documents/syslog-ng-ose-latest-guides/en/syslog-ng-ose-guide-admin/html/syslog-debun.1.html))

```
$ gdb syslog-ng
 run
```

## Steps to reproduce

1. start syslog-ng

2. ...

## Configuration

```
$ cat /path/to/syslog-ng.conf

```

(or gist URL)

## Input and output logs (if possible)

