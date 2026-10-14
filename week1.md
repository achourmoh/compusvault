
6.18.40.1-microsoft-standard-WSL2
PRETTY_NAME="Ubuntu 26.04.1 LTS"
NAME="Ubuntu"
VERSION_ID="26.04"
VERSION="26.04.1 LTS (Resolute Raccoon)"
VERSION_CODENAME=resolute
ID=ubuntu
ID_LIKE=debian
HOME_URL="https://www.ubuntu.com/"
SUPPORT_URL="https://help.ubuntu.com/"
BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
UBUNTU_CODENAME=resolute
LOGO=ubuntu-logo
windows
uid=1000(windows) gid=1000(windows) groups=1000(windows),4(adm),24(cdrom),27(sudo),30(dip),46(plugdev),100(users)
 USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root           1  0.0  0.1  24200 15364 ?        Ss   09:28   0:00 /sbin/init
root           2  0.0  0.0   3760  2332 hvc0     Sl+  09:28   0:00 /init
root           3  0.0  0.0   3612  2096 hvc0     S+   09:28   0:00 init-watcher
root           7  0.0  0.0   3760  2104 hvc0     Sl+  09:28   0:00 plan9 --control-socket 7 --log-level 4 --server-fd 8 --pipe-fd 10 --log-truncate
root          47  0.0  0.2  50676 18484 ?        S<s  09:28   0:00 /usr/lib/systemd/systemd-journald
systemd+      81  0.0  0.1  22428 14392 ?        Ss   09:28   0:00 /usr/lib/systemd/systemd-resolved
root          89  0.0  0.1  34800 12056 ?        Ss   09:28   0:01 /usr/lib/systemd/systemd-udevd
root         106  0.0  0.0   2888  2016 ?        Ss   09:28   0:00 /bin/sh /usr/lib/systemd/scripts/chronyd-starter.sh -n -F 1
root         107  0.0  0.0   4472  3136 ?        Ss   09:28   0:00 /usr/sbin/cron -f -P
message+     108  0.0  0.0   8824  5376 ?        Ss   09:28   0:00 @dbus-daemon --system --address=systemd: --nofork --nopidfile --systemd-activation --syslog-only
root         133  0.0  0.3  44112 29616 ?        Ss   09:28   0:00 /usr/bin/python3 /usr/bin/networkd-dispatcher --run-startup-triggers
root         157  0.0  0.1  18436  9468 ?        Ss   09:28   0:00 /usr/lib/systemd/systemd-logind
syslog       171  0.0  0.0 220548  5956 ?        Ssl  09:28   0:00 /usr/sbin/rsyslogd -n -iNONE
root         200  0.0  0.0   5492  2820 tty1     Ss+  09:28   0:00 /usr/sbin/agetty --noreset --noclear --issue-file=/etc/issue:/etc/issue.d:/run/issue.d:/usr/lib/issue.d - linux
State             Recv-Q            Send-Q                        Local Address:Port                        Peer Address:Port            Process
LISTEN            0                 4096                             127.0.0.54:53                               0.0.0.0:*
LISTEN            0                 1000                         10.255.255.254:53                               0.0.0.0:*
LISTEN            0                 4096                          127.0.0.53%lo:53                               0.0.0.0:*
  total        used        free      shared  buff/cache   available
Mem:           7.6Gi       550Mi       7.0Gi        34Mi       257Mi       7.1Gi
Swap:          2.0Gi          0B       2.0Gi

