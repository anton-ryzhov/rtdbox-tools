rtdbox-tools/bin
================

Полезные бинарные файлы, собранные для RTD1283-совместимых систем (ELF 32-bit LSB executable, MIPS, MIPS32 version 1).

**Busybox 1.15.3** был взял из проекта [OpenWRT](https://openwrt.org/).
Эта версия новее чем та, что идёт по умолчанию в Realtek SDK4, и содержит некоторые полезные апплеты.

Встроенные функции:
> [, [[, arping, ash, awk, basename, blkid, brctl, bunzip2, bzcat, cat, chgrp, chmod, chown, chroot, clear, cp, crond, crontab, cut, date, dd, df, diff, dirname, dmesg, du, echo, egrep, env, expr, false, fgrep, find, free, grep, gunzip, gzip, halt, head, hexdump, hostid, hwclock, id, ifconfig, init, insmod, kill, killall, killall5, klogd, length, less, ln, lock, logger, logread, ls, lsmod, md5sum, mesg, mkdir, mkfifo, mknod, mkswap, mktemp, mount, mv, nc, netmsg, netstat, nice, nslookup, ntpd, passwd, pgrep, pidof, ping, ping6, pivot_root, pkill, poweroff, printf, ps, pwd, reboot, reset, rm, rmdir, rmmod, route, sed, seq, sh, sleep, sort, start-stop-daemon, strings, swapoff, swapon, switch_root, sync, sysctl, syslogd, tail, tar, tee, telnet, telnetd, test, time, top, touch, tr, traceroute, true, udhcpc, umount, uname, uniq, uptime, vconfig, vi, watchdog, wc, wget, which, xargs, yes, zcat

**tthsum** был собран из [исходников](http://tthsum.devs.nu/) с помощью OpenWRT toolchain.

Другие подходящие бинарные файлы могут быть найдены в [репозитории OpenWRT](http://downloads.openwrt.org/backfire/10.03.1/brcm-2.4/packages)
