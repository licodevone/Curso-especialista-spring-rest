# Comandos no terminal

## Instalação do JRE e JDK Ubuntu

```sh
$ sudo apt update
Hit:1 http://archive.ubuntu.com/ubuntu jammy InRelease
Get:2 http://security.ubuntu.com/ubuntu jammy-security InRelease [129 kB]
Get:3 http://archive.ubuntu.com/ubuntu jammy-updates InRelease [128 kB]
Hit:4 http://archive.ubuntu.com/ubuntu jammy-backports InRelease
Fetched 257 kB in 2s (145 kB/s)
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
52 packages can be upgraded. Run 'apt list --upgradable' to see them.
```

```sh
$ sudo apt upgrade
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
Calculating upgrade... Done
The following NEW packages will be installed:
  ubuntu-pro-client
The following packages will be upgraded:
  apparmor apport apt apt-utils base-files coreutils distro-info dpkg e2fsprogs iptables irqbalance
  libapparmor1 libapt-pkg6.0 libcom-err2 libcryptsetup12 libext2fs2 libip4tc2 libip6tc2 libldap-2.5-0
  libldap-common libnss-systemd libpam-systemd libpcap0.8 libss2 libsystemd0 libudev1 libxtables12 logsave
  motd-news-config python-apt-common python3-apport python3-apt python3-distro-info python3-distupgrade
  python3-problem-report python3-software-properties python3-update-manager software-properties-common
  systemd systemd-hwe-hwdb systemd-sysv systemd-timesyncd tcpdump tzdata ubuntu-advantage-tools
  ubuntu-minimal ubuntu-pro-client-l10n ubuntu-release-upgrader-core ubuntu-standard ubuntu-wsl udev
  update-manager-core
52 upgraded, 1 newly installed, 0 to remove and 0 not upgraded.
Need to get 16.5 MB of archives.
After this operation, 253 kB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 motd-news-config all 12ubuntu4.7 [3822 B]
Get:2 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 base-files amd64 12ubuntu4.7 [61.9 kB]
Get:3 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 coreutils amd64 8.32-4.1ubuntu1.2 [1437 kB]
Get:4 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libnss-systemd amd64 249.11-0ubuntu3.12 [133 kB]
Get:5 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libsystemd0 amd64 249.11-0ubuntu3.12 [319 kB]
Get:6 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 systemd-timesyncd amd64 249.11-0ubuntu3.12 [31.2 kB]
Get:7 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 systemd-sysv amd64 249.11-0ubuntu3.12 [10.5 kB]
Get:8 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libpam-systemd amd64 249.11-0ubuntu3.12 [203 kB]
Get:9 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 systemd amd64 249.11-0ubuntu3.12 [4581 kB]
Get:10 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 udev amd64 249.11-0ubuntu3.12 [1557 kB]
Get:11 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libudev1 amd64 249.11-0ubuntu3.12 [78.2 kB]
Get:12 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libapparmor1 amd64 3.0.4-2ubuntu2.4 [39.7 kB]
Get:13 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libcryptsetup12 amd64 2:2.4.3-1ubuntu1.2 [211 kB]
Get:14 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libxtables12 amd64 1.8.7-1ubuntu5.2 [31.3 kB]
Get:15 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 iptables amd64 1.8.7-1ubuntu5.2 [455 kB]
Get:16 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libip6tc2 amd64 1.8.7-1ubuntu5.2 [20.3 kB]
Get:17 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libip4tc2 amd64 1.8.7-1ubuntu5.2 [19.9 kB]
Get:18 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libapt-pkg6.0 amd64 2.4.13 [912 kB]
Get:19 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 dpkg amd64 1.21.1ubuntu2.3 [1239 kB]
Get:20 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 apt amd64 2.4.13 [1363 kB]
Get:21 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 apt-utils amd64 2.4.13 [211 kB]
Get:22 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 logsave amd64 1.46.5-2ubuntu1.2 [10.1 kB]
Get:23 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libext2fs2 amd64 1.46.5-2ubuntu1.2 [208 kB]
Get:24 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 e2fsprogs amd64 1.46.5-2ubuntu1.2 [590 kB]
Get:25 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 irqbalance amd64 1.8.0-1ubuntu0.2 [47.2 kB]
Get:26 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libcom-err2 amd64 1.46.5-2ubuntu1.2 [9304 B]
Get:27 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libss2 amd64 1.46.5-2ubuntu1.2 [12.3 kB]
Get:28 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 distro-info amd64 1.1ubuntu0.2 [18.7 kB]
Get:29 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 python-apt-common all 2.4.0ubuntu4 [14.6 kB]
Get:30 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 python3-apt amd64 2.4.0ubuntu4 [164 kB]
Get:31 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 tzdata all 2024a-0ubuntu0.22.04.1 [349 kB]
Get:32 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 ubuntu-advantage-tools all 34~22.04 [10.9 kB]
Get:33 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 ubuntu-pro-client amd64 34~22.04 [221 kB]
Get:34 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 ubuntu-minimal amd64 1.481.3 [2742 B]
Get:35 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 ubuntu-pro-client-l10n amd64 34~22.04 [19.1 kB]
Get:36 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 apparmor amd64 3.0.4-2ubuntu2.4 [598 kB]
Get:37 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libpcap0.8 amd64 1.10.1-4ubuntu1.22.04.1 [145 kB]
Get:38 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 python3-distro-info all 1.1ubuntu0.2 [6554 B]
Get:39 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 ubuntu-release-upgrader-core all 1:22.04.20 [26.2 kB]
Get:40 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 python3-distupgrade all 1:22.04.20 [106 kB]
Get:41 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 python3-update-manager all 1:22.04.21 [39.1 kB]
Get:42 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 update-manager-core all 1:22.04.21 [11.5 kB]
Get:43 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 tcpdump amd64 4.99.1-3ubuntu0.2 [501 kB]
Get:44 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 ubuntu-standard amd64 1.481.3 [2764 B]
Get:45 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 python3-problem-report all 2.20.11-0ubuntu82.6 [11.1 kB]
Get:46 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 python3-apport all 2.20.11-0ubuntu82.6 [89.0 kB]
Get:47 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 apport all 2.20.11-0ubuntu82.6 [134 kB]
Get:48 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libldap-2.5-0 amd64 2.5.18+dfsg-0ubuntu0.22.04.2 [183 kB]
Get:49 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libldap-common all 2.5.18+dfsg-0ubuntu0.22.04.2 [15.9 kB]
Get:50 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 software-properties-common all 0.99.22.9 [14.1 kB]
Get:51 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 python3-software-properties all 0.99.22.9 [28.8 kB]
Get:52 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 systemd-hwe-hwdb all 249.11.5 [3228 B]
Get:53 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 ubuntu-wsl amd64 1.481.3 [2586 B]
Fetched 16.5 MB in 4s (4007 kB/s)
Extracting templates from packages: 100%
Preconfiguring packages ...
(Reading database ... 35867 files and directories currently installed.)
Preparing to unpack .../motd-news-config_12ubuntu4.7_all.deb ...
Unpacking motd-news-config (12ubuntu4.7) over (12ubuntu4.4) ...
Preparing to unpack .../base-files_12ubuntu4.7_amd64.deb ...
Unpacking base-files (12ubuntu4.7) over (12ubuntu4.4) ...
Setting up base-files (12ubuntu4.7) ...
Installing new version of config file /etc/issue ...
Installing new version of config file /etc/issue.net ...
Installing new version of config file /etc/lsb-release ...
Installing new version of config file /etc/update-motd.d/10-help-text ...
motd-news.service is a disabled or a static unit not running, not starting it.
(Reading database ... 35867 files and directories currently installed.)
Preparing to unpack .../coreutils_8.32-4.1ubuntu1.2_amd64.deb ...
Unpacking coreutils (8.32-4.1ubuntu1.2) over (8.32-4.1ubuntu1) ...
Setting up coreutils (8.32-4.1ubuntu1.2) ...
(Reading database ... 35867 files and directories currently installed.)
Preparing to unpack .../libnss-systemd_249.11-0ubuntu3.12_amd64.deb ...
Unpacking libnss-systemd:amd64 (249.11-0ubuntu3.12) over (249.11-0ubuntu3.11) ...
Preparing to unpack .../libsystemd0_249.11-0ubuntu3.12_amd64.deb ...
Unpacking libsystemd0:amd64 (249.11-0ubuntu3.12) over (249.11-0ubuntu3.11) ...
Setting up libsystemd0:amd64 (249.11-0ubuntu3.12) ...
(Reading database ... 35867 files and directories currently installed.)
Preparing to unpack .../0-systemd-timesyncd_249.11-0ubuntu3.12_amd64.deb ...
Unpacking systemd-timesyncd (249.11-0ubuntu3.12) over (249.11-0ubuntu3.11) ...
Preparing to unpack .../1-systemd-sysv_249.11-0ubuntu3.12_amd64.deb ...
Unpacking systemd-sysv (249.11-0ubuntu3.12) over (249.11-0ubuntu3.11) ...
Preparing to unpack .../2-libpam-systemd_249.11-0ubuntu3.12_amd64.deb ...
Unpacking libpam-systemd:amd64 (249.11-0ubuntu3.12) over (249.11-0ubuntu3.11) ...
Preparing to unpack .../3-systemd_249.11-0ubuntu3.12_amd64.deb ...
Unpacking systemd (249.11-0ubuntu3.12) over (249.11-0ubuntu3.11) ...
Preparing to unpack .../4-udev_249.11-0ubuntu3.12_amd64.deb ...
Unpacking udev (249.11-0ubuntu3.12) over (249.11-0ubuntu3.11) ...
Preparing to unpack .../5-libudev1_249.11-0ubuntu3.12_amd64.deb ...
Unpacking libudev1:amd64 (249.11-0ubuntu3.12) over (249.11-0ubuntu3.11) ...
Setting up libudev1:amd64 (249.11-0ubuntu3.12) ...
(Reading database ... 35867 files and directories currently installed.)
Preparing to unpack .../0-libapparmor1_3.0.4-2ubuntu2.4_amd64.deb ...
Unpacking libapparmor1:amd64 (3.0.4-2ubuntu2.4) over (3.0.4-2ubuntu2.3build2) ...
Preparing to unpack .../1-libcryptsetup12_2%3a2.4.3-1ubuntu1.2_amd64.deb ...
Unpacking libcryptsetup12:amd64 (2:2.4.3-1ubuntu1.2) over (2:2.4.3-1ubuntu1.1) ...
Preparing to unpack .../2-libxtables12_1.8.7-1ubuntu5.2_amd64.deb ...
Unpacking libxtables12:amd64 (1.8.7-1ubuntu5.2) over (1.8.7-1ubuntu5.1) ...
Preparing to unpack .../3-iptables_1.8.7-1ubuntu5.2_amd64.deb ...
Unpacking iptables (1.8.7-1ubuntu5.2) over (1.8.7-1ubuntu5.1) ...
Preparing to unpack .../4-libip6tc2_1.8.7-1ubuntu5.2_amd64.deb ...
Unpacking libip6tc2:amd64 (1.8.7-1ubuntu5.2) over (1.8.7-1ubuntu5.1) ...
Preparing to unpack .../5-libip4tc2_1.8.7-1ubuntu5.2_amd64.deb ...
Unpacking libip4tc2:amd64 (1.8.7-1ubuntu5.2) over (1.8.7-1ubuntu5.1) ...
Preparing to unpack .../6-libapt-pkg6.0_2.4.13_amd64.deb ...
Unpacking libapt-pkg6.0:amd64 (2.4.13) over (2.4.11) ...
Setting up libapt-pkg6.0:amd64 (2.4.13) ...
(Reading database ... 35867 files and directories currently installed.)
Preparing to unpack .../dpkg_1.21.1ubuntu2.3_amd64.deb ...
Unpacking dpkg (1.21.1ubuntu2.3) over (1.21.1ubuntu2.2) ...
Setting up dpkg (1.21.1ubuntu2.3) ...
dpkg-db-backup.service is a disabled or a static unit not running, not starting it.
(Reading database ... 35867 files and directories currently installed.)
Preparing to unpack .../archives/apt_2.4.13_amd64.deb ...
Unpacking apt (2.4.13) over (2.4.11) ...
Setting up apt (2.4.13) ...
(Reading database ... 35867 files and directories currently installed.)
Preparing to unpack .../apt-utils_2.4.13_amd64.deb ...
Unpacking apt-utils (2.4.13) over (2.4.11) ...
Preparing to unpack .../logsave_1.46.5-2ubuntu1.2_amd64.deb ...
Unpacking logsave (1.46.5-2ubuntu1.2) over (1.46.5-2ubuntu1.1) ...
Preparing to unpack .../libext2fs2_1.46.5-2ubuntu1.2_amd64.deb ...
Unpacking libext2fs2:amd64 (1.46.5-2ubuntu1.2) over (1.46.5-2ubuntu1.1) ...
Setting up libext2fs2:amd64 (1.46.5-2ubuntu1.2) ...
(Reading database ... 35867 files and directories currently installed.)
Preparing to unpack .../e2fsprogs_1.46.5-2ubuntu1.2_amd64.deb ...
Unpacking e2fsprogs (1.46.5-2ubuntu1.2) over (1.46.5-2ubuntu1.1) ...
Preparing to unpack .../irqbalance_1.8.0-1ubuntu0.2_amd64.deb ...
Unpacking irqbalance (1.8.0-1ubuntu0.2) over (1.8.0-1ubuntu0.1) ...
Preparing to unpack .../libcom-err2_1.46.5-2ubuntu1.2_amd64.deb ...
Unpacking libcom-err2:amd64 (1.46.5-2ubuntu1.2) over (1.46.5-2ubuntu1.1) ...
Setting up libcom-err2:amd64 (1.46.5-2ubuntu1.2) ...
(Reading database ... 35867 files and directories currently installed.)
Preparing to unpack .../00-libss2_1.46.5-2ubuntu1.2_amd64.deb ...
Unpacking libss2:amd64 (1.46.5-2ubuntu1.2) over (1.46.5-2ubuntu1.1) ...
Preparing to unpack .../01-distro-info_1.1ubuntu0.2_amd64.deb ...
Unpacking distro-info (1.1ubuntu0.2) over (1.1ubuntu0.1) ...
Preparing to unpack .../02-python-apt-common_2.4.0ubuntu4_all.deb ...
Unpacking python-apt-common (2.4.0ubuntu4) over (2.4.0ubuntu2) ...
Preparing to unpack .../03-python3-apt_2.4.0ubuntu4_amd64.deb ...
Unpacking python3-apt (2.4.0ubuntu4) over (2.4.0ubuntu2) ...
Preparing to unpack .../04-tzdata_2024a-0ubuntu0.22.04.1_all.deb ...
Unpacking tzdata (2024a-0ubuntu0.22.04.1) over (2024a-0ubuntu0.22.04) ...
Preparing to unpack .../05-ubuntu-advantage-tools_34~22.04_all.deb ...
Unpacking ubuntu-advantage-tools (34~22.04) over (30~22.04) ...
dpkg: warning: unable to delete old directory '/var/lib/ubuntu-advantage': Directory not empty
dpkg: warning: unable to delete old directory '/etc/ubuntu-advantage': Directory not empty
Selecting previously unselected package ubuntu-pro-client.
Preparing to unpack .../06-ubuntu-pro-client_34~22.04_amd64.deb ...
Unpacking ubuntu-pro-client (34~22.04) ...
Preparing to unpack .../07-ubuntu-minimal_1.481.3_amd64.deb ...
Unpacking ubuntu-minimal (1.481.3) over (1.481.1) ...
Preparing to unpack .../08-ubuntu-pro-client-l10n_34~22.04_amd64.deb ...
Unpacking ubuntu-pro-client-l10n (34~22.04) over (30~22.04) ...
Preparing to unpack .../09-apparmor_3.0.4-2ubuntu2.4_amd64.deb ...
Unpacking apparmor (3.0.4-2ubuntu2.4) over (3.0.4-2ubuntu2.3build2) ...
Preparing to unpack .../10-libpcap0.8_1.10.1-4ubuntu1.22.04.1_amd64.deb ...
Unpacking libpcap0.8:amd64 (1.10.1-4ubuntu1.22.04.1) over (1.10.1-4build1) ...
Preparing to unpack .../11-python3-distro-info_1.1ubuntu0.2_all.deb ...
Unpacking python3-distro-info (1.1ubuntu0.2) over (1.1ubuntu0.1) ...
Preparing to unpack .../12-ubuntu-release-upgrader-core_1%3a22.04.20_all.deb ...
Unpacking ubuntu-release-upgrader-core (1:22.04.20) over (1:22.04.17) ...
Preparing to unpack .../13-python3-distupgrade_1%3a22.04.20_all.deb ...
Unpacking python3-distupgrade (1:22.04.20) over (1:22.04.17) ...
Preparing to unpack .../14-python3-update-manager_1%3a22.04.21_all.deb ...
Unpacking python3-update-manager (1:22.04.21) over (1:22.04.10) ...
Preparing to unpack .../15-update-manager-core_1%3a22.04.21_all.deb ...
Unpacking update-manager-core (1:22.04.21) over (1:22.04.10) ...
Preparing to unpack .../16-tcpdump_4.99.1-3ubuntu0.2_amd64.deb ...
Unpacking tcpdump (4.99.1-3ubuntu0.2) over (4.99.1-3ubuntu0.1) ...
Preparing to unpack .../17-ubuntu-standard_1.481.3_amd64.deb ...
Unpacking ubuntu-standard (1.481.3) over (1.481.1) ...
Preparing to unpack .../18-python3-problem-report_2.20.11-0ubuntu82.6_all.deb ...
Unpacking python3-problem-report (2.20.11-0ubuntu82.6) over (2.20.11-0ubuntu82.5) ...
Preparing to unpack .../19-python3-apport_2.20.11-0ubuntu82.6_all.deb ...
Unpacking python3-apport (2.20.11-0ubuntu82.6) over (2.20.11-0ubuntu82.5) ...
Preparing to unpack .../20-apport_2.20.11-0ubuntu82.6_all.deb ...
Unpacking apport (2.20.11-0ubuntu82.6) over (2.20.11-0ubuntu82.5) ...
Preparing to unpack .../21-libldap-2.5-0_2.5.18+dfsg-0ubuntu0.22.04.2_amd64.deb ...
Unpacking libldap-2.5-0:amd64 (2.5.18+dfsg-0ubuntu0.22.04.2) over (2.5.16+dfsg-0ubuntu0.22.04.2) ...
Preparing to unpack .../22-libldap-common_2.5.18+dfsg-0ubuntu0.22.04.2_all.deb ...
Unpacking libldap-common (2.5.18+dfsg-0ubuntu0.22.04.2) over (2.5.16+dfsg-0ubuntu0.22.04.2) ...
Preparing to unpack .../23-software-properties-common_0.99.22.9_all.deb ...
Unpacking software-properties-common (0.99.22.9) over (0.99.22.8) ...
Preparing to unpack .../24-python3-software-properties_0.99.22.9_all.deb ...
Unpacking python3-software-properties (0.99.22.9) over (0.99.22.8) ...
Preparing to unpack .../25-systemd-hwe-hwdb_249.11.5_all.deb ...
Unpacking systemd-hwe-hwdb (249.11.5) over (249.11.3) ...
Preparing to unpack .../26-ubuntu-wsl_1.481.3_amd64.deb ...
Unpacking ubuntu-wsl (1.481.3) over (1.481.1) ...
Setting up libip4tc2:amd64 (1.8.7-1ubuntu5.2) ...
Setting up motd-news-config (12ubuntu4.7) ...
Setting up distro-info (1.1ubuntu0.2) ...
Setting up libapparmor1:amd64 (3.0.4-2ubuntu2.4) ...
Setting up apt-utils (2.4.13) ...
Setting up irqbalance (1.8.0-1ubuntu0.2) ...
Setting up python3-problem-report (2.20.11-0ubuntu82.6) ...
Setting up libip6tc2:amd64 (1.8.7-1ubuntu5.2) ...
Setting up libldap-common (2.5.18+dfsg-0ubuntu0.22.04.2) ...
Setting up libldap-2.5-0:amd64 (2.5.18+dfsg-0ubuntu0.22.04.2) ...
Setting up tzdata (2024a-0ubuntu0.22.04.1) ...

Current default time zone: 'America/Sao_Paulo'
Local time is now:      Sun Sep 22 20:31:11 -03 2024.
Universal Time is now:  Sun Sep 22 23:31:11 UTC 2024.
Run 'dpkg-reconfigure tzdata' if you wish to change it.

Setting up apparmor (3.0.4-2ubuntu2.4) ...
Setting up libpcap0.8:amd64 (1.10.1-4ubuntu1.22.04.1) ...
Setting up udev (249.11-0ubuntu3.12) ...
Setting up libss2:amd64 (1.46.5-2ubuntu1.2) ...
Setting up libxtables12:amd64 (1.8.7-1ubuntu5.2) ...
Setting up logsave (1.46.5-2ubuntu1.2) ...
Setting up systemd-hwe-hwdb (249.11.5) ...
Setting up python-apt-common (2.4.0ubuntu4) ...
Setting up libcryptsetup12:amd64 (2:2.4.3-1ubuntu1.2) ...
Setting up python3-distro-info (1.1ubuntu0.2) ...
Setting up tcpdump (4.99.1-3ubuntu0.2) ...
Installing new version of config file /etc/apparmor.d/usr.bin.tcpdump ...
Setting up iptables (1.8.7-1ubuntu5.2) ...
Setting up python3-apt (2.4.0ubuntu4) ...
Setting up e2fsprogs (1.46.5-2ubuntu1.2) ...
e2scrub_all.service is a disabled or a static unit not running, not starting it.
Setting up systemd (249.11-0ubuntu3.12) ...
Setting up python3-apport (2.20.11-0ubuntu82.6) ...
Setting up python3-software-properties (0.99.22.9) ...
Setting up systemd-timesyncd (249.11-0ubuntu3.12) ...
Setting up ubuntu-pro-client (34~22.04) ...
Setting up ubuntu-pro-client-l10n (34~22.04) ...
Setting up systemd-sysv (249.11-0ubuntu3.12) ...
Setting up libnss-systemd:amd64 (249.11-0ubuntu3.12) ...
Setting up software-properties-common (0.99.22.9) ...
Setting up apport (2.20.11-0ubuntu82.6) ...
apport-autoreport.service is a disabled or a static unit, not starting it.
Setting up libpam-systemd:amd64 (249.11-0ubuntu3.12) ...
Setting up ubuntu-advantage-tools (34~22.04) ...
Setting up ubuntu-minimal (1.481.3) ...
Setting up ubuntu-wsl (1.481.3) ...
Setting up ubuntu-standard (1.481.3) ...
Setting up python3-update-manager (1:22.04.21) ...
Setting up python3-distupgrade (1:22.04.20) ...
Setting up ubuntu-release-upgrader-core (1:22.04.20) ...
Setting up update-manager-core (1:22.04.21) ...
Processing triggers for install-info (6.8-4build1) ...
Processing triggers for libc-bin (2.35-0ubuntu3.8) ...
Processing triggers for man-db (2.10.2-1) ...
Processing triggers for plymouth-theme-ubuntu-text (0.9.5+git20211018-1ubuntu3) ...
Processing triggers for dbus (1.12.20-2ubuntu4.1) ...
```

## Instalação do OpenJDK através do repositório padrão do Ubuntu, procurar por pacotes disponíveis usando o comando "grep"

```sh
$ apt-cache search openjdk | grep openjdk-17
openjdk-17-dbg - Java runtime based on OpenJDK (debugging symbols)
openjdk-17-demo - Java runtime based on OpenJDK (demos and examples)
openjdk-17-doc - OpenJDK Development Kit (JDK) documentation
openjdk-17-jdk - OpenJDK Development Kit (JDK)
openjdk-17-jdk-headless - OpenJDK Development Kit (JDK) (headless)
openjdk-17-jre - OpenJDK Java runtime, using Hotspot JIT
openjdk-17-jre-headless - OpenJDK Java runtime, using Hotspot JIT (headless)
openjdk-17-jre-zero - Alternative JVM for OpenJDK, using Zero
openjdk-17-source - OpenJDK Development Kit (JDK) source files
```

## Instalação do JRE

```sh
$ sudo apt install openjdk-17-jre
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  adwaita-icon-theme alsa-topology-conf alsa-ucm-conf at-spi2-core ca-certificates-java
  dconf-gsettings-backend dconf-service fontconfig fonts-dejavu-extra gsettings-desktop-schemas
  gtk-update-icon-cache hicolor-icon-theme humanity-icon-theme java-common libasound2 libasound2-data
  libatk-bridge2.0-0 libatk-wrapper-java libatk-wrapper-java-jni libatk1.0-0 libatk1.0-data libatspi2.0-0
  libavahi-client3 libavahi-common-data libavahi-common3 libcairo-gobject2 libcairo2 libcups2 libdatrie1
  libdconf1 libdrm-amdgpu1 libdrm-intel1 libdrm-nouveau2 libdrm-radeon1 libfontenc1 libgail-common libgail18
  libgdk-pixbuf-2.0-0 libgdk-pixbuf2.0-bin libgdk-pixbuf2.0-common libgif7 libgl1 libgl1-amber-dri
  libgl1-mesa-dri libglapi-mesa libglvnd0 libglx-mesa0 libglx0 libgraphite2-3 libgtk2.0-0 libgtk2.0-bin
  libgtk2.0-common libharfbuzz0b libice6 liblcms2-2 libllvm15 libnspr4 libnss3 libpango-1.0-0
  libpangocairo-1.0-0 libpangoft2-1.0-0 libpciaccess0 libpcsclite1 libpixman-1-0 librsvg2-2 librsvg2-common
  libsensors-config libsensors5 libsm6 libthai-data libthai0 libx11-xcb1 libxaw7 libxcb-dri2-0 libxcb-dri3-0
  libxcb-glx0 libxcb-present0 libxcb-randr0 libxcb-render0 libxcb-shape0 libxcb-shm0 libxcb-sync1
  libxcb-xfixes0 libxcomposite1 libxcursor1 libxdamage1 libxfixes3 libxft2 libxi6 libxinerama1 libxkbfile1
  libxmu6 libxrandr2 libxrender1 libxshmfence1 libxt6 libxtst6 libxv1 libxxf86dga1 libxxf86vm1
  openjdk-17-jre-headless session-migration ubuntu-mono x11-common x11-utils
Suggested packages:
  default-jre libasound2-plugins alsa-utils cups-common gvfs liblcms2-utils pcscd librsvg2-bin lm-sensors
  libnss-mdns fonts-ipafont-gothic fonts-ipafont-mincho fonts-wqy-microhei | fonts-wqy-zenhei fonts-indic
  mesa-utils
The following NEW packages will be installed:
  adwaita-icon-theme alsa-topology-conf alsa-ucm-conf at-spi2-core ca-certificates-java
  dconf-gsettings-backend dconf-service fontconfig fonts-dejavu-extra gsettings-desktop-schemas
  gtk-update-icon-cache hicolor-icon-theme humanity-icon-theme java-common libasound2 libasound2-data
  libatk-bridge2.0-0 libatk-wrapper-java libatk-wrapper-java-jni libatk1.0-0 libatk1.0-data libatspi2.0-0
  libavahi-client3 libavahi-common-data libavahi-common3 libcairo-gobject2 libcairo2 libcups2 libdatrie1
  libdconf1 libdrm-amdgpu1 libdrm-intel1 libdrm-nouveau2 libdrm-radeon1 libfontenc1 libgail-common libgail18
  libgdk-pixbuf-2.0-0 libgdk-pixbuf2.0-bin libgdk-pixbuf2.0-common libgif7 libgl1 libgl1-amber-dri
  libgl1-mesa-dri libglapi-mesa libglvnd0 libglx-mesa0 libglx0 libgraphite2-3 libgtk2.0-0 libgtk2.0-bin
  libgtk2.0-common libharfbuzz0b libice6 liblcms2-2 libllvm15 libnspr4 libnss3 libpango-1.0-0
  libpangocairo-1.0-0 libpangoft2-1.0-0 libpciaccess0 libpcsclite1 libpixman-1-0 librsvg2-2 librsvg2-common
  libsensors-config libsensors5 libsm6 libthai-data libthai0 libx11-xcb1 libxaw7 libxcb-dri2-0 libxcb-dri3-0
  libxcb-glx0 libxcb-present0 libxcb-randr0 libxcb-render0 libxcb-shape0 libxcb-shm0 libxcb-sync1
  libxcb-xfixes0 libxcomposite1 libxcursor1 libxdamage1 libxfixes3 libxft2 libxi6 libxinerama1 libxkbfile1
  libxmu6 libxrandr2 libxrender1 libxshmfence1 libxt6 libxtst6 libxv1 libxxf86dga1 libxxf86vm1
  openjdk-17-jre openjdk-17-jre-headless session-migration ubuntu-mono x11-common x11-utils
0 upgraded, 106 newly installed, 0 to remove and 0 not upgraded.
Need to get 106 MB of archives.
After this operation, 442 MB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 hicolor-icon-theme all 0.17-2 [9976 B]
Get:2 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libgdk-pixbuf2.0-common all 2.42.8+dfsg-1ubuntu0.3 [5630 B]
Get:3 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libgdk-pixbuf-2.0-0 amd64 2.42.8+dfsg-1ubuntu0.3 [148 kB]
Get:4 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 gtk-update-icon-cache amd64 3.24.33-1ubuntu2.2 [31.4 kB]
Get:5 http://archive.ubuntu.com/ubuntu jammy/main amd64 humanity-icon-theme all 0.6.16 [1282 kB]
Get:6 http://archive.ubuntu.com/ubuntu jammy/main amd64 ubuntu-mono all 20.10-0ubuntu2 [153 kB]
Get:7 http://archive.ubuntu.com/ubuntu jammy/main amd64 adwaita-icon-theme all 41.0-1ubuntu1 [3444 kB]
Get:8 http://archive.ubuntu.com/ubuntu jammy/main amd64 alsa-topology-conf all 1.2.5.1-2 [15.5 kB]
Get:9 http://archive.ubuntu.com/ubuntu jammy/main amd64 libasound2-data all 1.2.6.1-1ubuntu1 [19.1 kB]
Get:10 http://archive.ubuntu.com/ubuntu jammy/main amd64 libasound2 amd64 1.2.6.1-1ubuntu1 [390 kB]
Get:11 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 alsa-ucm-conf all 1.2.6.3-1ubuntu1.11 [43.6 kB]
Get:12 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxi6 amd64 2:1.8-1build1 [32.6 kB]
Get:13 http://archive.ubuntu.com/ubuntu jammy/main amd64 libatspi2.0-0 amd64 2.44.0-3 [80.9 kB]
Get:14 http://archive.ubuntu.com/ubuntu jammy/main amd64 x11-common all 1:7.7+23ubuntu2 [23.4 kB]
Get:15 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxtst6 amd64 2:1.2.3-1build4 [13.4 kB]
Get:16 http://archive.ubuntu.com/ubuntu jammy/main amd64 libdconf1 amd64 0.40.0-3 [40.5 kB]
Get:17 http://archive.ubuntu.com/ubuntu jammy/main amd64 dconf-service amd64 0.40.0-3 [28.5 kB]
Get:18 http://archive.ubuntu.com/ubuntu jammy/main amd64 dconf-gsettings-backend amd64 0.40.0-3 [22.8 kB]
Get:19 http://archive.ubuntu.com/ubuntu jammy/main amd64 session-migration amd64 0.3.6 [9774 B]
Get:20 http://archive.ubuntu.com/ubuntu jammy/main amd64 gsettings-desktop-schemas all 42.0-1ubuntu1 [31.1 kB]
Get:21 http://archive.ubuntu.com/ubuntu jammy/main amd64 at-spi2-core amd64 2.44.0-3 [54.4 kB]
Get:22 http://archive.ubuntu.com/ubuntu jammy/main amd64 java-common all 0.72build2 [6782 B]
Get:23 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libavahi-common-data amd64 0.8-5ubuntu5.2 [23.8 kB]
Get:24 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libavahi-common3 amd64 0.8-5ubuntu5.2 [23.9 kB]
Get:25 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libavahi-client3 amd64 0.8-5ubuntu5.2 [28.0 kB]
Get:26 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libcups2 amd64 2.4.1op1-1ubuntu4.10 [263 kB]
Get:27 http://archive.ubuntu.com/ubuntu jammy/main amd64 liblcms2-2 amd64 2.12~rc1-2build2 [159 kB]
Get:28 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libnspr4 amd64 2:4.35-0ubuntu0.22.04.1 [119 kB]
Get:29 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libnss3 amd64 2:3.98-0ubuntu0.22.04.2 [1347 kB]
Get:30 http://archive.ubuntu.com/ubuntu jammy/main amd64 libgraphite2-3 amd64 1.3.14-1build2 [71.3 kB]
Get:31 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libharfbuzz0b amd64 2.7.4-1ubuntu3.1 [352 kB]
Get:32 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libpcsclite1 amd64 1.9.5-3ubuntu1 [19.8 kB]
Get:33 http://archive.ubuntu.com/ubuntu jammy-updates/universe amd64 openjdk-17-jre-headless amd64 17.0.12+7-1ubuntu2~22.04 [48.2 MB]
Get:34 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 ca-certificates-java all 20190909ubuntu1.2 [12.1 kB]
Get:35 http://archive.ubuntu.com/ubuntu jammy/main amd64 fontconfig amd64 2.13.1-4.2ubuntu5 [177 kB]
Get:36 http://archive.ubuntu.com/ubuntu jammy/main amd64 fonts-dejavu-extra all 2.37-2build1 [2041 kB]
Get:37 http://archive.ubuntu.com/ubuntu jammy/main amd64 libatk1.0-data all 2.36.0-3build1 [2824 B]
Get:38 http://archive.ubuntu.com/ubuntu jammy/main amd64 libatk1.0-0 amd64 2.36.0-3build1 [51.9 kB]
Get:39 http://archive.ubuntu.com/ubuntu jammy/main amd64 libatk-bridge2.0-0 amd64 2.38.0-3 [66.6 kB]
Get:40 http://archive.ubuntu.com/ubuntu jammy/main amd64 libfontenc1 amd64 1:1.1.4-1build3 [14.7 kB]
Get:41 http://archive.ubuntu.com/ubuntu jammy/main amd64 libglvnd0 amd64 1.4.0-1 [73.6 kB]
Get:42 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libglapi-mesa amd64 23.2.1-1ubuntu3.1~22.04.2 [37.1 kB]
Get:43 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libx11-xcb1 amd64 2:1.7.5-1ubuntu0.3 [7802 B]
Get:44 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxcb-dri2-0 amd64 1.14-3ubuntu3 [7206 B]
Get:45 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxcb-dri3-0 amd64 1.14-3ubuntu3 [6968 B]
Get:46 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxcb-glx0 amd64 1.14-3ubuntu3 [25.9 kB]
Get:47 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxcb-present0 amd64 1.14-3ubuntu3 [5734 B]
Get:48 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxcb-randr0 amd64 1.14-3ubuntu3 [18.3 kB]
Get:49 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxcb-shm0 amd64 1.14-3ubuntu3 [5780 B]
Get:50 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxcb-sync1 amd64 1.14-3ubuntu3 [9416 B]
Get:51 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxcb-xfixes0 amd64 1.14-3ubuntu3 [9996 B]
Get:52 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxfixes3 amd64 1:6.0.0-1 [11.7 kB]
Get:53 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxshmfence1 amd64 1.3-1build4 [5394 B]
Get:54 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxxf86vm1 amd64 1:1.1.4-1build3 [10.4 kB]
Get:55 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libdrm-amdgpu1 amd64 2.4.113-2~ubuntu0.22.04.1 [19.9 kB]
Get:56 http://archive.ubuntu.com/ubuntu jammy/main amd64 libpciaccess0 amd64 0.16-3 [19.1 kB]
Get:57 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libdrm-intel1 amd64 2.4.113-2~ubuntu0.22.04.1 [66.7 kB]
Get:58 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libdrm-nouveau2 amd64 2.4.113-2~ubuntu0.22.04.1 [17.5 kB]
Get:59 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libdrm-radeon1 amd64 2.4.113-2~ubuntu0.22.04.1 [21.6 kB]
Get:60 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libllvm15 amd64 1:15.0.7-0ubuntu0.22.04.3 [25.4 MB]
Get:61 http://archive.ubuntu.com/ubuntu jammy/main amd64 libsensors-config all 1:3.6.0-7ubuntu1 [5274 B]
Get:62 http://archive.ubuntu.com/ubuntu jammy/main amd64 libsensors5 amd64 1:3.6.0-7ubuntu1 [26.3 kB]
Get:63 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libgl1-mesa-dri amd64 23.2.1-1ubuntu3.1~22.04.2 [8860 kB]
Get:64 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libglx-mesa0 amd64 23.2.1-1ubuntu3.1~22.04.2 [158 kB]
Get:65 http://archive.ubuntu.com/ubuntu jammy/main amd64 libglx0 amd64 1.4.0-1 [41.0 kB]
Get:66 http://archive.ubuntu.com/ubuntu jammy/main amd64 libgl1 amd64 1.4.0-1 [110 kB]
Get:67 http://archive.ubuntu.com/ubuntu jammy/main amd64 libice6 amd64 2:1.0.10-1build2 [42.6 kB]
Get:68 http://archive.ubuntu.com/ubuntu jammy/main amd64 libsm6 amd64 2:1.2.3-1build2 [16.7 kB]
Get:69 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxt6 amd64 1:1.2.1-1 [177 kB]
Get:70 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxmu6 amd64 2:1.1.3-3 [49.6 kB]
Get:71 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxaw7 amd64 2:1.0.14-1 [191 kB]
Get:72 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxcb-shape0 amd64 1.14-3ubuntu3 [6158 B]
Get:73 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxcomposite1 amd64 1:0.4.5-1build2 [7192 B]
Get:74 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxrender1 amd64 1:0.9.10-1build4 [19.7 kB]
Get:75 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxft2 amd64 2.3.4-1 [41.8 kB]
Get:76 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxinerama1 amd64 2:1.1.4-3 [7382 B]
Get:77 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxkbfile1 amd64 1:1.1.0-1build3 [71.8 kB]
Get:78 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxrandr2 amd64 2:1.5.2-1build1 [20.4 kB]
Get:79 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxv1 amd64 2:1.0.11-1build2 [11.2 kB]
Get:80 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxxf86dga1 amd64 2:1.1.5-0ubuntu3 [12.6 kB]
Get:81 http://archive.ubuntu.com/ubuntu jammy/main amd64 x11-utils amd64 7.7+5build2 [206 kB]
Get:82 http://archive.ubuntu.com/ubuntu jammy/main amd64 libatk-wrapper-java all 0.38.0-5build1 [53.1 kB]
Get:83 http://archive.ubuntu.com/ubuntu jammy/main amd64 libatk-wrapper-java-jni amd64 0.38.0-5build1 [49.0 kB]
Get:84 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libpixman-1-0 amd64 0.40.0-1ubuntu0.22.04.1 [264 kB]
Get:85 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxcb-render0 amd64 1.14-3ubuntu3 [16.4 kB]
Get:86 http://archive.ubuntu.com/ubuntu jammy/main amd64 libcairo2 amd64 1.16.0-5ubuntu2 [628 kB]
Get:87 http://archive.ubuntu.com/ubuntu jammy/main amd64 libcairo-gobject2 amd64 1.16.0-5ubuntu2 [19.4 kB]
Get:88 http://archive.ubuntu.com/ubuntu jammy/main amd64 libdatrie1 amd64 0.2.13-2 [19.9 kB]
Get:89 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libgtk2.0-common all 2.24.33-2ubuntu2.1 [125 kB]
Get:90 http://archive.ubuntu.com/ubuntu jammy/main amd64 libthai-data all 0.1.29-1build1 [162 kB]
Get:91 http://archive.ubuntu.com/ubuntu jammy/main amd64 libthai0 amd64 0.1.29-1build1 [19.2 kB]
Get:92 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libpango-1.0-0 amd64 1.50.6+ds-2ubuntu1 [230 kB]
Get:93 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libpangoft2-1.0-0 amd64 1.50.6+ds-2ubuntu1 [54.0 kB]
Get:94 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libpangocairo-1.0-0 amd64 1.50.6+ds-2ubuntu1 [39.8 kB]
Get:95 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxcursor1 amd64 1:1.2.0-2build4 [20.9 kB]
Get:96 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxdamage1 amd64 1:1.1.5-2build2 [7154 B]
Get:97 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libgtk2.0-0 amd64 2.24.33-2ubuntu2.1 [2038 kB]
Get:98 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libgail18 amd64 2.24.33-2ubuntu2.1 [15.9 kB]
Get:99 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libgail-common amd64 2.24.33-2ubuntu2.1 [132 kB]
Get:100 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libgdk-pixbuf2.0-bin amd64 2.42.8+dfsg-1ubuntu0.3 [14.2 kB]
Get:101 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libgif7 amd64 5.1.9-2ubuntu0.1 [33.9 kB]
Get:102 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libgl1-amber-dri amd64 21.3.9-0ubuntu1~22.04.1 [4218 kB]
Get:103 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libgtk2.0-bin amd64 2.24.33-2ubuntu2.1 [7936 B]
Get:104 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 librsvg2-2 amd64 2.52.5+dfsg-3ubuntu0.2 [2974 kB]
Get:105 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 librsvg2-common amd64 2.52.5+dfsg-3ubuntu0.2 [17.7 kB]
Get:106 http://archive.ubuntu.com/ubuntu jammy-updates/universe amd64 openjdk-17-jre amd64 17.0.12+7-1ubuntu2~22.04 [203 kB]
Fetched 106 MB in 14s (7705 kB/s)
Extracting templates from packages: 100%
Selecting previously unselected package hicolor-icon-theme.
(Reading database ... 35915 files and directories currently installed.)
Preparing to unpack .../000-hicolor-icon-theme_0.17-2_all.deb ...
Unpacking hicolor-icon-theme (0.17-2) ...
Selecting previously unselected package libgdk-pixbuf2.0-common.
Preparing to unpack .../001-libgdk-pixbuf2.0-common_2.42.8+dfsg-1ubuntu0.3_all.deb ...
Unpacking libgdk-pixbuf2.0-common (2.42.8+dfsg-1ubuntu0.3) ...
Selecting previously unselected package libgdk-pixbuf-2.0-0:amd64.
Preparing to unpack .../002-libgdk-pixbuf-2.0-0_2.42.8+dfsg-1ubuntu0.3_amd64.deb ...
Unpacking libgdk-pixbuf-2.0-0:amd64 (2.42.8+dfsg-1ubuntu0.3) ...
Selecting previously unselected package gtk-update-icon-cache.
Preparing to unpack .../003-gtk-update-icon-cache_3.24.33-1ubuntu2.2_amd64.deb ...
Unpacking gtk-update-icon-cache (3.24.33-1ubuntu2.2) ...
Selecting previously unselected package humanity-icon-theme.
Preparing to unpack .../004-humanity-icon-theme_0.6.16_all.deb ...
Unpacking humanity-icon-theme (0.6.16) ...
Selecting previously unselected package ubuntu-mono.
Preparing to unpack .../005-ubuntu-mono_20.10-0ubuntu2_all.deb ...
Unpacking ubuntu-mono (20.10-0ubuntu2) ...
Selecting previously unselected package adwaita-icon-theme.
Preparing to unpack .../006-adwaita-icon-theme_41.0-1ubuntu1_all.deb ...
Unpacking adwaita-icon-theme (41.0-1ubuntu1) ...
Selecting previously unselected package alsa-topology-conf.
Preparing to unpack .../007-alsa-topology-conf_1.2.5.1-2_all.deb ...
Unpacking alsa-topology-conf (1.2.5.1-2) ...
Selecting previously unselected package libasound2-data.
Preparing to unpack .../008-libasound2-data_1.2.6.1-1ubuntu1_all.deb ...
Unpacking libasound2-data (1.2.6.1-1ubuntu1) ...
Selecting previously unselected package libasound2:amd64.
Preparing to unpack .../009-libasound2_1.2.6.1-1ubuntu1_amd64.deb ...
Unpacking libasound2:amd64 (1.2.6.1-1ubuntu1) ...
Selecting previously unselected package alsa-ucm-conf.
Preparing to unpack .../010-alsa-ucm-conf_1.2.6.3-1ubuntu1.11_all.deb ...
Unpacking alsa-ucm-conf (1.2.6.3-1ubuntu1.11) ...
Selecting previously unselected package libxi6:amd64.
Preparing to unpack .../011-libxi6_2%3a1.8-1build1_amd64.deb ...
Unpacking libxi6:amd64 (2:1.8-1build1) ...
Selecting previously unselected package libatspi2.0-0:amd64.
Preparing to unpack .../012-libatspi2.0-0_2.44.0-3_amd64.deb ...
Unpacking libatspi2.0-0:amd64 (2.44.0-3) ...
Selecting previously unselected package x11-common.
Preparing to unpack .../013-x11-common_1%3a7.7+23ubuntu2_all.deb ...
Unpacking x11-common (1:7.7+23ubuntu2) ...
Selecting previously unselected package libxtst6:amd64.
Preparing to unpack .../014-libxtst6_2%3a1.2.3-1build4_amd64.deb ...
Unpacking libxtst6:amd64 (2:1.2.3-1build4) ...
Selecting previously unselected package libdconf1:amd64.
Preparing to unpack .../015-libdconf1_0.40.0-3_amd64.deb ...
Unpacking libdconf1:amd64 (0.40.0-3) ...
Selecting previously unselected package dconf-service.
Preparing to unpack .../016-dconf-service_0.40.0-3_amd64.deb ...
Unpacking dconf-service (0.40.0-3) ...
Selecting previously unselected package dconf-gsettings-backend:amd64.
Preparing to unpack .../017-dconf-gsettings-backend_0.40.0-3_amd64.deb ...
Unpacking dconf-gsettings-backend:amd64 (0.40.0-3) ...
Selecting previously unselected package session-migration.
Preparing to unpack .../018-session-migration_0.3.6_amd64.deb ...
Unpacking session-migration (0.3.6) ...
Selecting previously unselected package gsettings-desktop-schemas.
Preparing to unpack .../019-gsettings-desktop-schemas_42.0-1ubuntu1_all.deb ...
Unpacking gsettings-desktop-schemas (42.0-1ubuntu1) ...
Selecting previously unselected package at-spi2-core.
Preparing to unpack .../020-at-spi2-core_2.44.0-3_amd64.deb ...
Unpacking at-spi2-core (2.44.0-3) ...
Selecting previously unselected package java-common.
Preparing to unpack .../021-java-common_0.72build2_all.deb ...
Unpacking java-common (0.72build2) ...
Selecting previously unselected package libavahi-common-data:amd64.
Preparing to unpack .../022-libavahi-common-data_0.8-5ubuntu5.2_amd64.deb ...
Unpacking libavahi-common-data:amd64 (0.8-5ubuntu5.2) ...
Selecting previously unselected package libavahi-common3:amd64.
Preparing to unpack .../023-libavahi-common3_0.8-5ubuntu5.2_amd64.deb ...
Unpacking libavahi-common3:amd64 (0.8-5ubuntu5.2) ...
Selecting previously unselected package libavahi-client3:amd64.
Preparing to unpack .../024-libavahi-client3_0.8-5ubuntu5.2_amd64.deb ...
Unpacking libavahi-client3:amd64 (0.8-5ubuntu5.2) ...
Selecting previously unselected package libcups2:amd64.
Preparing to unpack .../025-libcups2_2.4.1op1-1ubuntu4.10_amd64.deb ...
Unpacking libcups2:amd64 (2.4.1op1-1ubuntu4.10) ...
Selecting previously unselected package liblcms2-2:amd64.
Preparing to unpack .../026-liblcms2-2_2.12~rc1-2build2_amd64.deb ...
Unpacking liblcms2-2:amd64 (2.12~rc1-2build2) ...
Selecting previously unselected package libnspr4:amd64.
Preparing to unpack .../027-libnspr4_2%3a4.35-0ubuntu0.22.04.1_amd64.deb ...
Unpacking libnspr4:amd64 (2:4.35-0ubuntu0.22.04.1) ...
Selecting previously unselected package libnss3:amd64.
Preparing to unpack .../028-libnss3_2%3a3.98-0ubuntu0.22.04.2_amd64.deb ...
Unpacking libnss3:amd64 (2:3.98-0ubuntu0.22.04.2) ...
Selecting previously unselected package libgraphite2-3:amd64.
Preparing to unpack .../029-libgraphite2-3_1.3.14-1build2_amd64.deb ...
Unpacking libgraphite2-3:amd64 (1.3.14-1build2) ...
Selecting previously unselected package libharfbuzz0b:amd64.
Preparing to unpack .../030-libharfbuzz0b_2.7.4-1ubuntu3.1_amd64.deb ...
Unpacking libharfbuzz0b:amd64 (2.7.4-1ubuntu3.1) ...
Selecting previously unselected package libpcsclite1:amd64.
Preparing to unpack .../031-libpcsclite1_1.9.5-3ubuntu1_amd64.deb ...
Unpacking libpcsclite1:amd64 (1.9.5-3ubuntu1) ...
Selecting previously unselected package openjdk-17-jre-headless:amd64.
Preparing to unpack .../032-openjdk-17-jre-headless_17.0.12+7-1ubuntu2~22.04_amd64.deb ...
Unpacking openjdk-17-jre-headless:amd64 (17.0.12+7-1ubuntu2~22.04) ...
Selecting previously unselected package ca-certificates-java.
Preparing to unpack .../033-ca-certificates-java_20190909ubuntu1.2_all.deb ...
Unpacking ca-certificates-java (20190909ubuntu1.2) ...
Selecting previously unselected package fontconfig.
Preparing to unpack .../034-fontconfig_2.13.1-4.2ubuntu5_amd64.deb ...
Unpacking fontconfig (2.13.1-4.2ubuntu5) ...
Selecting previously unselected package fonts-dejavu-extra.
Preparing to unpack .../035-fonts-dejavu-extra_2.37-2build1_all.deb ...
Unpacking fonts-dejavu-extra (2.37-2build1) ...
Selecting previously unselected package libatk1.0-data.
Preparing to unpack .../036-libatk1.0-data_2.36.0-3build1_all.deb ...
Unpacking libatk1.0-data (2.36.0-3build1) ...
Selecting previously unselected package libatk1.0-0:amd64.
Preparing to unpack .../037-libatk1.0-0_2.36.0-3build1_amd64.deb ...
Unpacking libatk1.0-0:amd64 (2.36.0-3build1) ...
Selecting previously unselected package libatk-bridge2.0-0:amd64.
Preparing to unpack .../038-libatk-bridge2.0-0_2.38.0-3_amd64.deb ...
Unpacking libatk-bridge2.0-0:amd64 (2.38.0-3) ...
Selecting previously unselected package libfontenc1:amd64.
Preparing to unpack .../039-libfontenc1_1%3a1.1.4-1build3_amd64.deb ...
Unpacking libfontenc1:amd64 (1:1.1.4-1build3) ...
Selecting previously unselected package libglvnd0:amd64.
Preparing to unpack .../040-libglvnd0_1.4.0-1_amd64.deb ...
Unpacking libglvnd0:amd64 (1.4.0-1) ...
Selecting previously unselected package libglapi-mesa:amd64.
Preparing to unpack .../041-libglapi-mesa_23.2.1-1ubuntu3.1~22.04.2_amd64.deb ...
Unpacking libglapi-mesa:amd64 (23.2.1-1ubuntu3.1~22.04.2) ...
Selecting previously unselected package libx11-xcb1:amd64.
Preparing to unpack .../042-libx11-xcb1_2%3a1.7.5-1ubuntu0.3_amd64.deb ...
Unpacking libx11-xcb1:amd64 (2:1.7.5-1ubuntu0.3) ...
Selecting previously unselected package libxcb-dri2-0:amd64.
Preparing to unpack .../043-libxcb-dri2-0_1.14-3ubuntu3_amd64.deb ...
Unpacking libxcb-dri2-0:amd64 (1.14-3ubuntu3) ...
Selecting previously unselected package libxcb-dri3-0:amd64.
Preparing to unpack .../044-libxcb-dri3-0_1.14-3ubuntu3_amd64.deb ...
Unpacking libxcb-dri3-0:amd64 (1.14-3ubuntu3) ...
Selecting previously unselected package libxcb-glx0:amd64.
Preparing to unpack .../045-libxcb-glx0_1.14-3ubuntu3_amd64.deb ...
Unpacking libxcb-glx0:amd64 (1.14-3ubuntu3) ...
Selecting previously unselected package libxcb-present0:amd64.
Preparing to unpack .../046-libxcb-present0_1.14-3ubuntu3_amd64.deb ...
Unpacking libxcb-present0:amd64 (1.14-3ubuntu3) ...
Selecting previously unselected package libxcb-randr0:amd64.
Preparing to unpack .../047-libxcb-randr0_1.14-3ubuntu3_amd64.deb ...
Unpacking libxcb-randr0:amd64 (1.14-3ubuntu3) ...
Selecting previously unselected package libxcb-shm0:amd64.
Preparing to unpack .../048-libxcb-shm0_1.14-3ubuntu3_amd64.deb ...
Unpacking libxcb-shm0:amd64 (1.14-3ubuntu3) ...
Selecting previously unselected package libxcb-sync1:amd64.
Preparing to unpack .../049-libxcb-sync1_1.14-3ubuntu3_amd64.deb ...
Unpacking libxcb-sync1:amd64 (1.14-3ubuntu3) ...
Selecting previously unselected package libxcb-xfixes0:amd64.
Preparing to unpack .../050-libxcb-xfixes0_1.14-3ubuntu3_amd64.deb ...
Unpacking libxcb-xfixes0:amd64 (1.14-3ubuntu3) ...
Selecting previously unselected package libxfixes3:amd64.
Preparing to unpack .../051-libxfixes3_1%3a6.0.0-1_amd64.deb ...
Unpacking libxfixes3:amd64 (1:6.0.0-1) ...
Selecting previously unselected package libxshmfence1:amd64.
Preparing to unpack .../052-libxshmfence1_1.3-1build4_amd64.deb ...
Unpacking libxshmfence1:amd64 (1.3-1build4) ...
Selecting previously unselected package libxxf86vm1:amd64.
Preparing to unpack .../053-libxxf86vm1_1%3a1.1.4-1build3_amd64.deb ...
Unpacking libxxf86vm1:amd64 (1:1.1.4-1build3) ...
Selecting previously unselected package libdrm-amdgpu1:amd64.
Preparing to unpack .../054-libdrm-amdgpu1_2.4.113-2~ubuntu0.22.04.1_amd64.deb ...
Unpacking libdrm-amdgpu1:amd64 (2.4.113-2~ubuntu0.22.04.1) ...
Selecting previously unselected package libpciaccess0:amd64.
Preparing to unpack .../055-libpciaccess0_0.16-3_amd64.deb ...
Unpacking libpciaccess0:amd64 (0.16-3) ...
Selecting previously unselected package libdrm-intel1:amd64.
Preparing to unpack .../056-libdrm-intel1_2.4.113-2~ubuntu0.22.04.1_amd64.deb ...
Unpacking libdrm-intel1:amd64 (2.4.113-2~ubuntu0.22.04.1) ...
Selecting previously unselected package libdrm-nouveau2:amd64.
Preparing to unpack .../057-libdrm-nouveau2_2.4.113-2~ubuntu0.22.04.1_amd64.deb ...
Unpacking libdrm-nouveau2:amd64 (2.4.113-2~ubuntu0.22.04.1) ...
Selecting previously unselected package libdrm-radeon1:amd64.
Preparing to unpack .../058-libdrm-radeon1_2.4.113-2~ubuntu0.22.04.1_amd64.deb ...
Unpacking libdrm-radeon1:amd64 (2.4.113-2~ubuntu0.22.04.1) ...
Selecting previously unselected package libllvm15:amd64.
Preparing to unpack .../059-libllvm15_1%3a15.0.7-0ubuntu0.22.04.3_amd64.deb ...
Unpacking libllvm15:amd64 (1:15.0.7-0ubuntu0.22.04.3) ...
Selecting previously unselected package libsensors-config.
Preparing to unpack .../060-libsensors-config_1%3a3.6.0-7ubuntu1_all.deb ...
Unpacking libsensors-config (1:3.6.0-7ubuntu1) ...
Selecting previously unselected package libsensors5:amd64.
Preparing to unpack .../061-libsensors5_1%3a3.6.0-7ubuntu1_amd64.deb ...
Unpacking libsensors5:amd64 (1:3.6.0-7ubuntu1) ...
Selecting previously unselected package libgl1-mesa-dri:amd64.
Preparing to unpack .../062-libgl1-mesa-dri_23.2.1-1ubuntu3.1~22.04.2_amd64.deb ...
Unpacking libgl1-mesa-dri:amd64 (23.2.1-1ubuntu3.1~22.04.2) ...
Selecting previously unselected package libglx-mesa0:amd64.
Preparing to unpack .../063-libglx-mesa0_23.2.1-1ubuntu3.1~22.04.2_amd64.deb ...
Unpacking libglx-mesa0:amd64 (23.2.1-1ubuntu3.1~22.04.2) ...
Selecting previously unselected package libglx0:amd64.
Preparing to unpack .../064-libglx0_1.4.0-1_amd64.deb ...
Unpacking libglx0:amd64 (1.4.0-1) ...
Selecting previously unselected package libgl1:amd64.
Preparing to unpack .../065-libgl1_1.4.0-1_amd64.deb ...
Unpacking libgl1:amd64 (1.4.0-1) ...
Selecting previously unselected package libice6:amd64.
Preparing to unpack .../066-libice6_2%3a1.0.10-1build2_amd64.deb ...
Unpacking libice6:amd64 (2:1.0.10-1build2) ...
Selecting previously unselected package libsm6:amd64.
Preparing to unpack .../067-libsm6_2%3a1.2.3-1build2_amd64.deb ...
Unpacking libsm6:amd64 (2:1.2.3-1build2) ...
Selecting previously unselected package libxt6:amd64.
Preparing to unpack .../068-libxt6_1%3a1.2.1-1_amd64.deb ...
Unpacking libxt6:amd64 (1:1.2.1-1) ...
Selecting previously unselected package libxmu6:amd64.
Preparing to unpack .../069-libxmu6_2%3a1.1.3-3_amd64.deb ...
Unpacking libxmu6:amd64 (2:1.1.3-3) ...
Selecting previously unselected package libxaw7:amd64.
Preparing to unpack .../070-libxaw7_2%3a1.0.14-1_amd64.deb ...
Unpacking libxaw7:amd64 (2:1.0.14-1) ...
Selecting previously unselected package libxcb-shape0:amd64.
Preparing to unpack .../071-libxcb-shape0_1.14-3ubuntu3_amd64.deb ...
Unpacking libxcb-shape0:amd64 (1.14-3ubuntu3) ...
Selecting previously unselected package libxcomposite1:amd64.
Preparing to unpack .../072-libxcomposite1_1%3a0.4.5-1build2_amd64.deb ...
Unpacking libxcomposite1:amd64 (1:0.4.5-1build2) ...
Selecting previously unselected package libxrender1:amd64.
Preparing to unpack .../073-libxrender1_1%3a0.9.10-1build4_amd64.deb ...
Unpacking libxrender1:amd64 (1:0.9.10-1build4) ...
Selecting previously unselected package libxft2:amd64.
Preparing to unpack .../074-libxft2_2.3.4-1_amd64.deb ...
Unpacking libxft2:amd64 (2.3.4-1) ...
Selecting previously unselected package libxinerama1:amd64.
Preparing to unpack .../075-libxinerama1_2%3a1.1.4-3_amd64.deb ...
Unpacking libxinerama1:amd64 (2:1.1.4-3) ...
Selecting previously unselected package libxkbfile1:amd64.
Preparing to unpack .../076-libxkbfile1_1%3a1.1.0-1build3_amd64.deb ...
Unpacking libxkbfile1:amd64 (1:1.1.0-1build3) ...
Selecting previously unselected package libxrandr2:amd64.
Preparing to unpack .../077-libxrandr2_2%3a1.5.2-1build1_amd64.deb ...
Unpacking libxrandr2:amd64 (2:1.5.2-1build1) ...
Selecting previously unselected package libxv1:amd64.
Preparing to unpack .../078-libxv1_2%3a1.0.11-1build2_amd64.deb ...
Unpacking libxv1:amd64 (2:1.0.11-1build2) ...
Selecting previously unselected package libxxf86dga1:amd64.
Preparing to unpack .../079-libxxf86dga1_2%3a1.1.5-0ubuntu3_amd64.deb ...
Unpacking libxxf86dga1:amd64 (2:1.1.5-0ubuntu3) ...
Selecting previously unselected package x11-utils.
Preparing to unpack .../080-x11-utils_7.7+5build2_amd64.deb ...
Unpacking x11-utils (7.7+5build2) ...
Selecting previously unselected package libatk-wrapper-java.
Preparing to unpack .../081-libatk-wrapper-java_0.38.0-5build1_all.deb ...
Unpacking libatk-wrapper-java (0.38.0-5build1) ...
Selecting previously unselected package libatk-wrapper-java-jni:amd64.
Preparing to unpack .../082-libatk-wrapper-java-jni_0.38.0-5build1_amd64.deb ...
Unpacking libatk-wrapper-java-jni:amd64 (0.38.0-5build1) ...
Selecting previously unselected package libpixman-1-0:amd64.
Preparing to unpack .../083-libpixman-1-0_0.40.0-1ubuntu0.22.04.1_amd64.deb ...
Unpacking libpixman-1-0:amd64 (0.40.0-1ubuntu0.22.04.1) ...
Selecting previously unselected package libxcb-render0:amd64.
Preparing to unpack .../084-libxcb-render0_1.14-3ubuntu3_amd64.deb ...
Unpacking libxcb-render0:amd64 (1.14-3ubuntu3) ...
Selecting previously unselected package libcairo2:amd64.
Preparing to unpack .../085-libcairo2_1.16.0-5ubuntu2_amd64.deb ...
Unpacking libcairo2:amd64 (1.16.0-5ubuntu2) ...
Selecting previously unselected package libcairo-gobject2:amd64.
Preparing to unpack .../086-libcairo-gobject2_1.16.0-5ubuntu2_amd64.deb ...
Unpacking libcairo-gobject2:amd64 (1.16.0-5ubuntu2) ...
Selecting previously unselected package libdatrie1:amd64.
Preparing to unpack .../087-libdatrie1_0.2.13-2_amd64.deb ...
Unpacking libdatrie1:amd64 (0.2.13-2) ...
Selecting previously unselected package libgtk2.0-common.
Preparing to unpack .../088-libgtk2.0-common_2.24.33-2ubuntu2.1_all.deb ...
Unpacking libgtk2.0-common (2.24.33-2ubuntu2.1) ...
Selecting previously unselected package libthai-data.
Preparing to unpack .../089-libthai-data_0.1.29-1build1_all.deb ...
Unpacking libthai-data (0.1.29-1build1) ...
Selecting previously unselected package libthai0:amd64.
Preparing to unpack .../090-libthai0_0.1.29-1build1_amd64.deb ...
Unpacking libthai0:amd64 (0.1.29-1build1) ...
Selecting previously unselected package libpango-1.0-0:amd64.
Preparing to unpack .../091-libpango-1.0-0_1.50.6+ds-2ubuntu1_amd64.deb ...
Unpacking libpango-1.0-0:amd64 (1.50.6+ds-2ubuntu1) ...
Selecting previously unselected package libpangoft2-1.0-0:amd64.
Preparing to unpack .../092-libpangoft2-1.0-0_1.50.6+ds-2ubuntu1_amd64.deb ...
Unpacking libpangoft2-1.0-0:amd64 (1.50.6+ds-2ubuntu1) ...
Selecting previously unselected package libpangocairo-1.0-0:amd64.
Preparing to unpack .../093-libpangocairo-1.0-0_1.50.6+ds-2ubuntu1_amd64.deb ...
Unpacking libpangocairo-1.0-0:amd64 (1.50.6+ds-2ubuntu1) ...
Selecting previously unselected package libxcursor1:amd64.
Preparing to unpack .../094-libxcursor1_1%3a1.2.0-2build4_amd64.deb ...
Unpacking libxcursor1:amd64 (1:1.2.0-2build4) ...
Selecting previously unselected package libxdamage1:amd64.
Preparing to unpack .../095-libxdamage1_1%3a1.1.5-2build2_amd64.deb ...
Unpacking libxdamage1:amd64 (1:1.1.5-2build2) ...
Selecting previously unselected package libgtk2.0-0:amd64.
Preparing to unpack .../096-libgtk2.0-0_2.24.33-2ubuntu2.1_amd64.deb ...
Unpacking libgtk2.0-0:amd64 (2.24.33-2ubuntu2.1) ...
Selecting previously unselected package libgail18:amd64.
Preparing to unpack .../097-libgail18_2.24.33-2ubuntu2.1_amd64.deb ...
Unpacking libgail18:amd64 (2.24.33-2ubuntu2.1) ...
Selecting previously unselected package libgail-common:amd64.
Preparing to unpack .../098-libgail-common_2.24.33-2ubuntu2.1_amd64.deb ...
Unpacking libgail-common:amd64 (2.24.33-2ubuntu2.1) ...
Selecting previously unselected package libgdk-pixbuf2.0-bin.
Preparing to unpack .../099-libgdk-pixbuf2.0-bin_2.42.8+dfsg-1ubuntu0.3_amd64.deb ...
Unpacking libgdk-pixbuf2.0-bin (2.42.8+dfsg-1ubuntu0.3) ...
Selecting previously unselected package libgif7:amd64.
Preparing to unpack .../100-libgif7_5.1.9-2ubuntu0.1_amd64.deb ...
Unpacking libgif7:amd64 (5.1.9-2ubuntu0.1) ...
Selecting previously unselected package libgl1-amber-dri:amd64.
Preparing to unpack .../101-libgl1-amber-dri_21.3.9-0ubuntu1~22.04.1_amd64.deb ...
Unpacking libgl1-amber-dri:amd64 (21.3.9-0ubuntu1~22.04.1) ...
Selecting previously unselected package libgtk2.0-bin.
Preparing to unpack .../102-libgtk2.0-bin_2.24.33-2ubuntu2.1_amd64.deb ...
Unpacking libgtk2.0-bin (2.24.33-2ubuntu2.1) ...
Selecting previously unselected package librsvg2-2:amd64.
Preparing to unpack .../103-librsvg2-2_2.52.5+dfsg-3ubuntu0.2_amd64.deb ...
Unpacking librsvg2-2:amd64 (2.52.5+dfsg-3ubuntu0.2) ...
Selecting previously unselected package librsvg2-common:amd64.
Preparing to unpack .../104-librsvg2-common_2.52.5+dfsg-3ubuntu0.2_amd64.deb ...
Unpacking librsvg2-common:amd64 (2.52.5+dfsg-3ubuntu0.2) ...
Selecting previously unselected package openjdk-17-jre:amd64.
Preparing to unpack .../105-openjdk-17-jre_17.0.12+7-1ubuntu2~22.04_amd64.deb ...
Unpacking openjdk-17-jre:amd64 (17.0.12+7-1ubuntu2~22.04) ...
Setting up libgraphite2-3:amd64 (1.3.14-1build2) ...
Setting up libxcb-dri3-0:amd64 (1.14-3ubuntu3) ...
Setting up liblcms2-2:amd64 (2.12~rc1-2build2) ...
Setting up libpixman-1-0:amd64 (0.40.0-1ubuntu0.22.04.1) ...
Setting up libx11-xcb1:amd64 (2:1.7.5-1ubuntu0.3) ...
Setting up libpciaccess0:amd64 (0.16-3) ...
Setting up session-migration (0.3.6) ...
Created symlink /etc/systemd/user/graphical-session-pre.target.wants/session-migration.service → /usr/lib/systemd/user/session-migration.service.
Setting up fontconfig (2.13.1-4.2ubuntu5) ...
Regenerating fonts cache... done.
Setting up libdrm-nouveau2:amd64 (2.4.113-2~ubuntu0.22.04.1) ...
Setting up libxdamage1:amd64 (1:1.1.5-2build2) ...
Setting up libxcb-xfixes0:amd64 (1.14-3ubuntu3) ...
Setting up hicolor-icon-theme (0.17-2) ...
Setting up libxi6:amd64 (2:1.8-1build1) ...
Setting up java-common (0.72build2) ...
Setting up libxrender1:amd64 (1:0.9.10-1build4) ...
Setting up libdatrie1:amd64 (0.2.13-2) ...
Setting up libxcb-render0:amd64 (1.14-3ubuntu3) ...
Setting up libdrm-radeon1:amd64 (2.4.113-2~ubuntu0.22.04.1) ...
Setting up libglvnd0:amd64 (1.4.0-1) ...
Setting up libxcb-glx0:amd64 (1.14-3ubuntu3) ...
Setting up libdrm-intel1:amd64 (2.4.113-2~ubuntu0.22.04.1) ...
Setting up libgdk-pixbuf2.0-common (2.42.8+dfsg-1ubuntu0.3) ...
Setting up libxcb-shape0:amd64 (1.14-3ubuntu3) ...
Setting up x11-common (1:7.7+23ubuntu2) ...
Setting up libsensors-config (1:3.6.0-7ubuntu1) ...
Setting up libxxf86dga1:amd64 (2:1.1.5-0ubuntu3) ...
Setting up libxcb-shm0:amd64 (1.14-3ubuntu3) ...
Setting up libatspi2.0-0:amd64 (2.44.0-3) ...
Setting up libcairo2:amd64 (1.16.0-5ubuntu2) ...
Setting up libxxf86vm1:amd64 (1:1.1.4-1build3) ...
Setting up libxcb-present0:amd64 (1.14-3ubuntu3) ...
Setting up libdconf1:amd64 (0.40.0-3) ...
Setting up libasound2-data (1.2.6.1-1ubuntu1) ...
Setting up libfontenc1:amd64 (1:1.1.4-1build3) ...
Setting up libnspr4:amd64 (2:4.35-0ubuntu0.22.04.1) ...
Setting up libxfixes3:amd64 (1:6.0.0-1) ...
Setting up libxcb-sync1:amd64 (1.14-3ubuntu3) ...
Setting up libavahi-common-data:amd64 (0.8-5ubuntu5.2) ...
Setting up libxinerama1:amd64 (2:1.1.4-3) ...
Setting up libxv1:amd64 (2:1.0.11-1build2) ...
Setting up libxrandr2:amd64 (2:1.5.2-1build1) ...
Setting up libpcsclite1:amd64 (1.9.5-3ubuntu1) ...
Setting up libsensors5:amd64 (1:3.6.0-7ubuntu1) ...
Setting up libglapi-mesa:amd64 (23.2.1-1ubuntu3.1~22.04.2) ...
Setting up libxcb-dri2-0:amd64 (1.14-3ubuntu3) ...
Setting up libgif7:amd64 (5.1.9-2ubuntu0.1) ...
Setting up libatk1.0-data (2.36.0-3build1) ...
Setting up fonts-dejavu-extra (2.37-2build1) ...
Setting up alsa-topology-conf (1.2.5.1-2) ...
Setting up libxshmfence1:amd64 (1.3-1build4) ...
Setting up libxcb-randr0:amd64 (1.14-3ubuntu3) ...
Setting up libllvm15:amd64 (1:15.0.7-0ubuntu0.22.04.3) ...
Setting up libasound2:amd64 (1.2.6.1-1ubuntu1) ...
Setting up libharfbuzz0b:amd64 (2.7.4-1ubuntu3.1) ...
Setting up libthai-data (0.1.29-1build1) ...
Setting up libgdk-pixbuf-2.0-0:amd64 (2.42.8+dfsg-1ubuntu0.3) ...
Setting up libcairo-gobject2:amd64 (1.16.0-5ubuntu2) ...
Setting up libgtk2.0-common (2.24.33-2ubuntu2.1) ...
Setting up libatk1.0-0:amd64 (2.36.0-3build1) ...
Setting up libxkbfile1:amd64 (1:1.1.0-1build3) ...
Setting up libxcomposite1:amd64 (1:0.4.5-1build2) ...
Setting up libdrm-amdgpu1:amd64 (2.4.113-2~ubuntu0.22.04.1) ...
Setting up libgl1-amber-dri:amd64 (21.3.9-0ubuntu1~22.04.1) ...
Setting up gtk-update-icon-cache (3.24.33-1ubuntu2.2) ...
Setting up libice6:amd64 (2:1.0.10-1build2) ...
Setting up libxft2:amd64 (2.3.4-1) ...
Setting up alsa-ucm-conf (1.2.6.3-1ubuntu1.11) ...
Setting up libxtst6:amd64 (2:1.2.3-1build4) ...
Setting up libxcursor1:amd64 (1:1.2.0-2build4) ...
Setting up libgl1-mesa-dri:amd64 (23.2.1-1ubuntu3.1~22.04.2) ...
Setting up libavahi-common3:amd64 (0.8-5ubuntu5.2) ...
Setting up dconf-service (0.40.0-3) ...
Setting up libnss3:amd64 (2:3.98-0ubuntu0.22.04.2) ...
Setting up libatk-bridge2.0-0:amd64 (2.38.0-3) ...
Setting up libthai0:amd64 (0.1.29-1build1) ...
Setting up libgdk-pixbuf2.0-bin (2.42.8+dfsg-1ubuntu0.3) ...
Setting up libsm6:amd64 (2:1.2.3-1build2) ...
Setting up libavahi-client3:amd64 (0.8-5ubuntu5.2) ...
Setting up libglx-mesa0:amd64 (23.2.1-1ubuntu3.1~22.04.2) ...
Setting up libglx0:amd64 (1.4.0-1) ...
Setting up dconf-gsettings-backend:amd64 (0.40.0-3) ...
Setting up libpango-1.0-0:amd64 (1.50.6+ds-2ubuntu1) ...
Setting up libgl1:amd64 (1.4.0-1) ...
Setting up libxt6:amd64 (1:1.2.1-1) ...
Setting up libcups2:amd64 (2.4.1op1-1ubuntu4.10) ...
Setting up libpangoft2-1.0-0:amd64 (1.50.6+ds-2ubuntu1) ...
Setting up libpangocairo-1.0-0:amd64 (1.50.6+ds-2ubuntu1) ...
Setting up gsettings-desktop-schemas (42.0-1ubuntu1) ...
Setting up libxmu6:amd64 (2:1.1.3-3) ...
Setting up libxaw7:amd64 (2:1.0.14-1) ...
Setting up librsvg2-2:amd64 (2.52.5+dfsg-3ubuntu0.2) ...
Setting up librsvg2-common:amd64 (2.52.5+dfsg-3ubuntu0.2) ...
Setting up x11-utils (7.7+5build2) ...
Setting up libatk-wrapper-java (0.38.0-5build1) ...
Setting up libatk-wrapper-java-jni:amd64 (0.38.0-5build1) ...
Setting up openjdk-17-jre-headless:amd64 (17.0.12+7-1ubuntu2~22.04) ...
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/java to provide /usr/bin/java (java) in auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jpackage to provide /usr/bin/jpackage (jpackage) in auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/keytool to provide /usr/bin/keytool (keytool
) in auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/rmiregistry to provide /usr/bin/rmiregistry (rmiregistry) in auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/lib/jexec to provide /usr/bin/jexec (jexec) in a
uto mode
Setting up ca-certificates-java (20190909ubuntu1.2) ...
head: cannot open '/etc/ssl/certs/java/cacerts' for reading: No such file or directory
Adding debian:Certum_Trusted_Network_CA.pem
Adding debian:Amazon_Root_CA_4.pem
Adding debian:Security_Communication_Root_CA.pem
Adding debian:vTrus_Root_CA.pem
Adding debian:QuoVadis_Root_CA_3.pem
Adding debian:DigiCert_Global_Root_G2.pem
Adding debian:Security_Communication_ECC_RootCA1.pem
Adding debian:DigiCert_TLS_ECC_P384_Root_G5.pem
Adding debian:OISTE_WISeKey_Global_Root_GC_CA.pem
Adding debian:DigiCert_Global_Root_CA.pem
Adding debian:DigiCert_High_Assurance_EV_Root_CA.pem
Adding debian:Atos_TrustedRoot_2011.pem
Adding debian:GlobalSign_Root_CA_-_R3.pem
Adding debian:TUBITAK_Kamu_SM_SSL_Kok_Sertifikasi_-_Surum_1.pem
Adding debian:Microsoft_RSA_Root_Certificate_Authority_2017.pem
Adding debian:Certigna_Root_CA.pem
Adding debian:Trustwave_Global_Certification_Authority.pem
Adding debian:Amazon_Root_CA_1.pem
Adding debian:Security_Communication_RootCA2.pem
Adding debian:QuoVadis_Root_CA_3_G3.pem
Adding debian:ANF_Secure_Server_Root_CA.pem
Adding debian:GTS_Root_R4.pem
Adding debian:emSign_ECC_Root_CA_-_G3.pem
Adding debian:vTrus_ECC_Root_CA.pem
Adding debian:GlobalSign_Root_E46.pem
Adding debian:E-Tugra_Certification_Authority.pem
Adding debian:T-TeleSec_GlobalRoot_Class_3.pem
Adding debian:QuoVadis_Root_CA_1_G3.pem
Adding debian:DigiCert_Global_Root_G3.pem
Adding debian:GlobalSign_Root_CA.pem
Adding debian:TWCA_Global_Root_CA.pem
Adding debian:GlobalSign_Root_CA_-_R6.pem
Adding debian:Entrust.net_Premium_2048_Secure_Server_CA.pem
Adding debian:SZAFIR_ROOT_CA2.pem
Adding debian:UCA_Extended_Validation_Root.pem
Adding debian:e-Szigno_Root_CA_2017.pem
Adding debian:DigiCert_TLS_RSA4096_Root_G5.pem
Adding debian:AffirmTrust_Networking.pem
Adding debian:IdenTrust_Public_Sector_Root_CA_1.pem
Adding debian:Autoridad_de_Certificacion_Firmaprofesional_CIF_A62634068_2.pem
Adding debian:certSIGN_ROOT_CA.pem
Adding debian:QuoVadis_Root_CA_2_G3.pem
Adding debian:Amazon_Root_CA_2.pem
Adding debian:Secure_Global_CA.pem
Adding debian:CFCA_EV_ROOT.pem
Adding debian:SecureTrust_CA.pem
Adding debian:NAVER_Global_Root_Certification_Authority.pem
Adding debian:AC_RAIZ_FNMT-RCM.pem
Adding debian:Certum_Trusted_Root_CA.pem
Adding debian:QuoVadis_Root_CA_2.pem
Adding debian:SwissSign_Gold_CA_-_G2.pem
Adding debian:Hellenic_Academic_and_Research_Institutions_RootCA_2015.pem
Adding debian:DigiCert_Assured_ID_Root_G2.pem
Adding debian:COMODO_ECC_Certification_Authority.pem
Adding debian:Entrust_Root_Certification_Authority_-_EC1.pem
Adding debian:AffirmTrust_Premium_ECC.pem
Adding debian:Trustwave_Global_ECC_P384_Certification_Authority.pem
Adding debian:Microsec_e-Szigno_Root_CA_2009.pem
Adding debian:emSign_Root_CA_-_G1.pem
Adding debian:DigiCert_Trusted_Root_G4.pem
Adding debian:COMODO_Certification_Authority.pem
Adding debian:DigiCert_Assured_ID_Root_G3.pem
Adding debian:Starfield_Services_Root_Certificate_Authority_-_G2.pem
Adding debian:AC_RAIZ_FNMT-RCM_SERVIDORES_SEGUROS.pem
Adding debian:IdenTrust_Commercial_Root_CA_1.pem
Adding debian:UCA_Global_G2_Root.pem
Adding debian:Izenpe.com.pem
Adding debian:Buypass_Class_2_Root_CA.pem
Adding debian:NetLock_Arany_=Class_Gold=_Főtanúsítvány.pem
Adding debian:AffirmTrust_Premium.pem
Adding debian:Comodo_AAA_Services_root.pem
Adding debian:GTS_Root_R2.pem
Adding debian:TWCA_Root_Certification_Authority.pem
Adding debian:Entrust_Root_Certification_Authority_-_G2.pem
Adding debian:GDCA_TrustAUTH_R5_ROOT.pem
Adding debian:HARICA_TLS_RSA_Root_CA_2021.pem
Adding debian:USERTrust_RSA_Certification_Authority.pem
Adding debian:GlobalSign_ECC_Root_CA_-_R4.pem
Adding debian:T-TeleSec_GlobalRoot_Class_2.pem
Adding debian:Certum_Trusted_Network_CA_2.pem
Adding debian:SwissSign_Silver_CA_-_G2.pem
Adding debian:GTS_Root_R1.pem
Adding debian:Trustwave_Global_ECC_P256_Certification_Authority.pem
Adding debian:D-TRUST_Root_Class_3_CA_2_EV_2009.pem
Adding debian:certSIGN_Root_CA_G2.pem
Adding debian:Certum_EC-384_CA.pem
Adding debian:E-Tugra_Global_Root_CA_ECC_v3.pem
Adding debian:Amazon_Root_CA_3.pem
Adding debian:D-TRUST_EV_Root_CA_1_2020.pem
Adding debian:Hongkong_Post_Root_CA_3.pem
Adding debian:D-TRUST_BR_Root_CA_1_2020.pem
Adding debian:GlobalSign_Root_R46.pem
Adding debian:SSL.com_Root_Certification_Authority_RSA.pem
Adding debian:GTS_Root_R3.pem
Adding debian:SSL.com_EV_Root_Certification_Authority_ECC.pem
Adding debian:D-TRUST_Root_Class_3_CA_2_2009.pem
Adding debian:Security_Communication_RootCA3.pem
Adding debian:GlobalSign_ECC_Root_CA_-_R5.pem
Adding debian:Go_Daddy_Class_2_CA.pem
Adding debian:SSL.com_Root_Certification_Authority_ECC.pem
Adding debian:Microsoft_ECC_Root_Certificate_Authority_2017.pem
Adding debian:SSL.com_EV_Root_Certification_Authority_RSA_R2.pem
Adding debian:TeliaSonera_Root_CA_v1.pem
Adding debian:Certainly_Root_R1.pem
Adding debian:GLOBALTRUST_2020.pem
Adding debian:Hellenic_Academic_and_Research_Institutions_ECC_RootCA_2015.pem
Adding debian:HiPKI_Root_CA_-_G1.pem
Adding debian:ACCVRAIZ1.pem
Adding debian:Certigna.pem
Adding debian:CA_Disig_Root_R2.pem
Adding debian:Starfield_Root_Certificate_Authority_-_G2.pem
Adding debian:Telia_Root_CA_v2.pem
Adding debian:Starfield_Class_2_CA.pem
Adding debian:OISTE_WISeKey_Global_Root_GB_CA.pem
Adding debian:XRamp_Global_CA_Root.pem
Adding debian:HARICA_TLS_ECC_Root_CA_2021.pem
Adding debian:Buypass_Class_3_Root_CA.pem
Adding debian:ePKI_Root_Certification_Authority.pem
Adding debian:DigiCert_Assured_ID_Root_CA.pem
Adding debian:ISRG_Root_X1.pem
Adding debian:Certainly_Root_E1.pem
Adding debian:emSign_ECC_Root_CA_-_C3.pem
Adding debian:Entrust_Root_Certification_Authority.pem
Adding debian:Hongkong_Post_Root_CA_1.pem
Adding debian:emSign_Root_CA_-_C1.pem
Adding debian:SecureSign_RootCA11.pem
Adding debian:AffirmTrust_Commercial.pem
Adding debian:Entrust_Root_Certification_Authority_-_G4.pem
Adding debian:TunTrust_Root_CA.pem
Adding debian:Baltimore_CyberTrust_Root.pem
Adding debian:COMODO_RSA_Certification_Authority.pem
Adding debian:E-Tugra_Global_Root_CA_RSA_v3.pem
Adding debian:Go_Daddy_Root_Certificate_Authority_-_G2.pem
Adding debian:USERTrust_ECC_Certification_Authority.pem
Adding debian:ISRG_Root_X2.pem
Adding debian:Actalis_Authentication_Root_CA.pem
Adding debian:Autoridad_de_Certificacion_Firmaprofesional_CIF_A62634068.pem
done.
Setting up adwaita-icon-theme (41.0-1ubuntu1) ...
update-alternatives: using /usr/share/icons/Adwaita/cursor.theme to provide /usr/share/icons/default/index.theme (x-cursor-theme) in auto mode
Setting up libgtk2.0-0:amd64 (2.24.33-2ubuntu2.1) ...
Setting up humanity-icon-theme (0.6.16) ...
Setting up libgail18:amd64 (2.24.33-2ubuntu2.1) ...
Setting up libgtk2.0-bin (2.24.33-2ubuntu2.1) ...
Setting up libgail-common:amd64 (2.24.33-2ubuntu2.1) ...
Setting up openjdk-17-jre:amd64 (17.0.12+7-1ubuntu2~22.04) ...
Setting up ubuntu-mono (20.10-0ubuntu2) ...
Processing triggers for man-db (2.10.2-1) ...
Processing triggers for ca-certificates (20230311ubuntu0.22.04.1) ...
Updating certificates in /etc/ssl/certs...
0 added, 0 removed; done.
Running hooks in /etc/ca-certificates/update.d...

done.
done.
Processing triggers for libglib2.0-0:amd64 (2.72.4-0ubuntu2.3) ...
Processing triggers for libc-bin (2.35-0ubuntu3.8) ...
Setting up at-spi2-core (2.44.0-3) ...
Processing triggers for libgdk-pixbuf-2.0-0:amd64 (2.42.8+dfsg-1ubuntu0.3) ...
```

## Instalação do JDK

```sh
$ sudo apt install openjdk-17-jdk
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  libice-dev libpthread-stubs0-dev libsm-dev libx11-dev libxau-dev libxcb1-dev libxdmcp-dev libxt-dev
  openjdk-17-jdk-headless x11proto-dev xorg-sgml-doctools xtrans-dev
Suggested packages:
  libice-doc libsm-doc libx11-doc libxcb-doc libxt-doc openjdk-17-demo openjdk-17-source visualvm
The following NEW packages will be installed:
  libice-dev libpthread-stubs0-dev libsm-dev libx11-dev libxau-dev libxcb1-dev libxdmcp-dev libxt-dev
  openjdk-17-jdk openjdk-17-jdk-headless x11proto-dev xorg-sgml-doctools xtrans-dev
0 upgraded, 13 newly installed, 0 to remove and 0 not upgraded.
Need to get 75.6 MB of archives.
After this operation, 88.2 MB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 xorg-sgml-doctools all 1:1.11-1.1 [10.9 kB]
Get:2 http://archive.ubuntu.com/ubuntu jammy/main amd64 x11proto-dev all 2021.5-1 [604 kB]
Get:3 http://archive.ubuntu.com/ubuntu jammy/main amd64 libice-dev amd64 2:1.0.10-1build2 [51.4 kB]
Get:4 http://archive.ubuntu.com/ubuntu jammy/main amd64 libpthread-stubs0-dev amd64 0.4-1build2 [5516 B]
Get:5 http://archive.ubuntu.com/ubuntu jammy/main amd64 libsm-dev amd64 2:1.2.3-1build2 [18.1 kB]
Get:6 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxau-dev amd64 1:1.0.9-1build5 [9724 B]
Get:7 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxdmcp-dev amd64 1:1.1.3-0ubuntu5 [26.5 kB]
Get:8 http://archive.ubuntu.com/ubuntu jammy/main amd64 xtrans-dev all 1.4.0-1 [68.9 kB]
Get:9 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxcb1-dev amd64 1.14-3ubuntu3 [86.5 kB]
Get:10 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 libx11-dev amd64 2:1.7.5-1ubuntu0.3 [744 kB]
Get:11 http://archive.ubuntu.com/ubuntu jammy/main amd64 libxt-dev amd64 1:1.2.1-1 [396 kB]
Get:12 http://archive.ubuntu.com/ubuntu jammy-updates/universe amd64 openjdk-17-jdk-headless amd64 17.0.12+7-1ubuntu2~22.04 [71.2 MB]
Get:13 http://archive.ubuntu.com/ubuntu jammy-updates/universe amd64 openjdk-17-jdk amd64 17.0.12+7-1ubuntu2~22.04 [2376 kB]
Fetched 75.6 MB in 5s (14.4 MB/s)
Selecting previously unselected package xorg-sgml-doctools.
(Reading database ... 51379 files and directories currently installed.)
Preparing to unpack .../00-xorg-sgml-doctools_1%3a1.11-1.1_all.deb ...
Unpacking xorg-sgml-doctools (1:1.11-1.1) ...
Selecting previously unselected package x11proto-dev.
Preparing to unpack .../01-x11proto-dev_2021.5-1_all.deb ...
Unpacking x11proto-dev (2021.5-1) ...
Selecting previously unselected package libice-dev:amd64.
Preparing to unpack .../02-libice-dev_2%3a1.0.10-1build2_amd64.deb ...
Unpacking libice-dev:amd64 (2:1.0.10-1build2) ...
Selecting previously unselected package libpthread-stubs0-dev:amd64.
Preparing to unpack .../03-libpthread-stubs0-dev_0.4-1build2_amd64.deb ...
Unpacking libpthread-stubs0-dev:amd64 (0.4-1build2) ...
Selecting previously unselected package libsm-dev:amd64.
Preparing to unpack .../04-libsm-dev_2%3a1.2.3-1build2_amd64.deb ...
Unpacking libsm-dev:amd64 (2:1.2.3-1build2) ...
Selecting previously unselected package libxau-dev:amd64.
Preparing to unpack .../05-libxau-dev_1%3a1.0.9-1build5_amd64.deb ...
Unpacking libxau-dev:amd64 (1:1.0.9-1build5) ...
Selecting previously unselected package libxdmcp-dev:amd64.
Preparing to unpack .../06-libxdmcp-dev_1%3a1.1.3-0ubuntu5_amd64.deb ...
Unpacking libxdmcp-dev:amd64 (1:1.1.3-0ubuntu5) ...
Selecting previously unselected package xtrans-dev.
Preparing to unpack .../07-xtrans-dev_1.4.0-1_all.deb ...
Unpacking xtrans-dev (1.4.0-1) ...
Selecting previously unselected package libxcb1-dev:amd64.
Preparing to unpack .../08-libxcb1-dev_1.14-3ubuntu3_amd64.deb ...
Unpacking libxcb1-dev:amd64 (1.14-3ubuntu3) ...
Selecting previously unselected package libx11-dev:amd64.
Preparing to unpack .../09-libx11-dev_2%3a1.7.5-1ubuntu0.3_amd64.deb ...
Unpacking libx11-dev:amd64 (2:1.7.5-1ubuntu0.3) ...
Selecting previously unselected package libxt-dev:amd64.
Preparing to unpack .../10-libxt-dev_1%3a1.2.1-1_amd64.deb ...
Unpacking libxt-dev:amd64 (1:1.2.1-1) ...
Selecting previously unselected package openjdk-17-jdk-headless:amd64.
Preparing to unpack .../11-openjdk-17-jdk-headless_17.0.12+7-1ubuntu2~22.04_amd64.deb ...
Unpacking openjdk-17-jdk-headless:amd64 (17.0.12+7-1ubuntu2~22.04) ...
Selecting previously unselected package openjdk-17-jdk:amd64.
Preparing to unpack .../12-openjdk-17-jdk_17.0.12+7-1ubuntu2~22.04_amd64.deb ...
Unpacking openjdk-17-jdk:amd64 (17.0.12+7-1ubuntu2~22.04) ...
Setting up libpthread-stubs0-dev:amd64 (0.4-1build2) ...
Setting up xtrans-dev (1.4.0-1) ...
Setting up openjdk-17-jdk-headless:amd64 (17.0.12+7-1ubuntu2~22.04) ...
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jar to provide /usr/bin/jar (jar) in auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jarsigner to provide /usr/bin/jarsigner (jarsigner) in auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/javac to provide /usr/bin/javac (javac) in auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/javadoc to provide /usr/bin/javadoc (javadoc
) in auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/javap to provide /usr/bin/javap (javap) in auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jcmd to provide /usr/bin/jcmd (jcmd) in auto
 mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jdb to provide /usr/bin/jdb (jdb) in auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jdeprscan to provide /usr/bin/jdeprscan (jde
prscan) in auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jdeps to provide /usr/bin/jdeps (jdeps) in auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jfr to provide /usr/bin/jfr (jfr) in auto mo
de
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jimage to provide /usr/bin/jimage (jimage) in auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jinfo to provide /usr/bin/jinfo (jinfo) in a
uto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jlink to provide /usr/bin/jlink (jlink) in auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jmap to provide /usr/bin/jmap (jmap) in auto
 mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jmod to provide /usr/bin/jmod (jmod) in auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jps to provide /usr/bin/jps (jps) in auto mo
de
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jrunscript to provide /usr/bin/jrunscript (jrunscript) in auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jshell to provide /usr/bin/jshell (jshell) i
n auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jstack to provide /usr/bin/jstack (jstack) in auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jstat to provide /usr/bin/jstat (jstat) in auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jstatd to provide /usr/bin/jstatd (jstatd) i
n auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/serialver to provide /usr/bin/serialver (serialver) in auto mode
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jhsdb to provide /usr/bin/jhsdb (jhsdb) in a
uto mode
Setting up xorg-sgml-doctools (1:1.11-1.1) ...
Setting up x11proto-dev (2021.5-1) ...
Setting up libxau-dev:amd64 (1:1.0.9-1build5) ...
Setting up libice-dev:amd64 (2:1.0.10-1build2) ...
Setting up libsm-dev:amd64 (2:1.2.3-1build2) ...
Setting up openjdk-17-jdk:amd64 (17.0.12+7-1ubuntu2~22.04) ...
update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jconsole to provide /usr/bin/jconsole (jconsole) in auto mode
Setting up libxdmcp-dev:amd64 (1:1.1.3-0ubuntu5) ...
Setting up libxcb1-dev:amd64 (1.14-3ubuntu3) ...
Setting up libx11-dev:amd64 (2:1.7.5-1ubuntu0.3) ...
Setting up libxt-dev:amd64 (1:1.2.1-1) ...
Processing triggers for man-db (2.10.2-1) ...
```

## Verificar as versões do JRE e JDK

```sh
$ java -version
openjdk 17.0.12 2024-07-16
OpenJDK Runtime Environment (build 17.0.12+7-Ubuntu-1ubuntu222.04)
OpenJDK 64-Bit Server VM (build 17.0.12+7-Ubuntu-1ubuntu222.04, mixed mode, sharing)
```

```sh
$ javac -version
javac 17.0.12
```
## Escolher a versão do JDK

https://warcontent.com/update-alternatives-linux/

```sh
$ sudo update-alternatives --list java
/usr/lib/jvm/java-17-openjdk-amd64/bin/java
```

```sh
~$ sudo update-alternatives --config java
There are 2 choices for the alternative java (providing /usr/bin/java).

  Selection    Path                                         Priority   Status
------------------------------------------------------------
* 0            /usr/lib/jvm/java-17-openjdk-amd64/bin/java   1711      auto mode
  1            /usr/lib/jvm/java-11-openjdk-amd64/bin/java   1111      manual mode
  2            /usr/lib/jvm/java-17-openjdk-amd64/bin/java   1711      manual mode

Press <enter> to keep the current choice[*], or type selection number: 2
```
## Para remover uma ou todas as alternativas

```sh
$ sudo update-alternatives --remove java /opt/jdk8/bin/java
```

```sh
 sudo update-alternatives --remove-all java
```
## Configurando o JAVA_HOME

```sh
$ cat ~/.bashrc
# ~/.bashrc: executed by bash(1) for non-login shells.
# see /usr/share/doc/bash/examples/startup-files (in the package bash-doc)
# for examples

# If not running interactively, don't do anything
case $- in
    *i*) ;;
      *) return;;
esac

# don't put duplicate lines or lines starting with space in the history.
# See bash(1) for more options
HISTCONTROL=ignoreboth

# append to the history file, don't overwrite it
shopt -s histappend

# for setting history length see HISTSIZE and HISTFILESIZE in bash(1)
HISTSIZE=1000
HISTFILESIZE=2000

# check the window size after each command and, if necessary,
# update the values of LINES and COLUMNS.
shopt -s checkwinsize

# If set, the pattern "**" used in a pathname expansion context will
# match all files and zero or more directories and subdirectories.
#shopt -s globstar

# make less more friendly for non-text input files, see lesspipe(1)
[ -x /usr/bin/lesspipe ] && eval "$(SHELL=/bin/sh lesspipe)"

# set variable identifying the chroot you work in (used in the prompt below)
if [ -z "${debian_chroot:-}" ] && [ -r /etc/debian_chroot ]; then
    debian_chroot=$(cat /etc/debian_chroot)
fi

# set a fancy prompt (non-color, unless we know we "want" color)
case "$TERM" in
    xterm-color|*-256color) color_prompt=yes;;
esac

# uncomment for a colored prompt, if the terminal has the capability; turned
# off by default to not distract the user: the focus in a terminal window
# should be on the output of commands, not on the prompt
#force_color_prompt=yes

if [ -n "$force_color_prompt" ]; then
    if [ -x /usr/bin/tput ] && tput setaf 1 >&/dev/null; then
        # We have color support; assume it's compliant with Ecma-48
        # (ISO/IEC-6429). (Lack of such support is extremely rare, and such
        # a case would tend to support setf rather than setaf.)
        color_prompt=yes
    else
        color_prompt=
    fi
fi

if [ "$color_prompt" = yes ]; then
    PS1='${debian_chroot:+($debian_chroot)}\[\033[01;32m\]\u@\h\[\033[00m\]:\[\033[01;34m\]\w\[\033[00m\]\$ '
else
    PS1='${debian_chroot:+($debian_chroot)}\u@\h:\w\$ '
fi
unset color_prompt force_color_prompt

# If this is an xterm set the title to user@host:dir
case "$TERM" in
xterm*|rxvt*)
    PS1="\[\e]0;${debian_chroot:+($debian_chroot)}\u@\h: \w\a\]$PS1"
    ;;
*)
    ;;
esac

# enable color support of ls and also add handy aliases
if [ -x /usr/bin/dircolors ]; then
    test -r ~/.dircolors && eval "$(dircolors -b ~/.dircolors)" || eval "$(dircolors -b)"
    alias ls='ls --color=auto'
    #alias dir='dir --color=auto'
    #alias vdir='vdir --color=auto'

    alias grep='grep --color=auto'
    alias fgrep='fgrep --color=auto'
    alias egrep='egrep --color=auto'
fi

# colored GCC warnings and errors
#export GCC_COLORS='error=01;31:warning=01;35:note=01;36:caret=01;32:locus=01:quote=01'

# some more ls aliases
alias ll='ls -alF'
alias la='ls -A'
alias l='ls -CF'

# Add an "alert" alias for long running commands.  Use like so:
#   sleep 10; alert
alias alert='notify-send --urgency=low -i "$([ $? = 0 ] && echo terminal || echo error)" "$(history|tail -n1|sed -e '\''s/^\s*[0-9]\+\s*//;s/[;&|]\s*alert$//'\'')"'

# Alias definitions.
# You may want to put all your additions into a separate file like
# ~/.bash_aliases, instead of adding them here directly.
# See /usr/share/doc/bash-doc/examples in the bash-doc package.

if [ -f ~/.bash_aliases ]; then
    . ~/.bash_aliases
fi

# enable programmable completion features (you don't need to enable
# this, if it's already enabled in /etc/bash.bashrc and /etc/profile
# sources /etc/bash.bashrc).
if ! shopt -oq posix; then
  if [ -f /usr/share/bash-completion/bash_completion ]; then
    . /usr/share/bash-completion/bash_completion
  elif [ -f /etc/bash_completion ]; then
    . /etc/bash_completion
  fi
fi

. $HOME/esp/esp-idf/export.sh


JAVA_HOME=/usr/lib/jvm/java-17-openjdk-amd64
export JAVA_HOME
export PATH=$PATH:$JAVA_HOME
licodev@lesp:~$ echo $JAVA_HOME
/usr/lib/jvm/java-17-openjdk-amd64
```

```sh
$ echo $JAVA_HOME
/usr/lib/jvm/java-17-openjdk-amd64
```


# Empacotamento com o Maven

```sh
[INFO] Scanning for projects...
[WARNING] The requested profile "pom.xml" could not be activated because it does not exist.
[INFO] 
[INFO] [1m---------------------< [0;36mcom.algaworks:algafood-api[0;1m >---------------------[m
[INFO] [1mBuilding algafood-api 0.0.1-SNAPSHOT[m
[INFO]   from pom.xml
[INFO] [1m--------------------------------[ jar ]---------------------------------[m
[INFO] 
[INFO] [1m--- [0;32mresources:3.2.0:resources[m [1m(default-resources)[m @ [36malgafood-api[0;1m ---[m
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] Using 'UTF-8' encoding to copy filtered properties files.
[INFO] Copying 1 resource
[INFO] Copying 0 resource
[INFO] 
[INFO] [1m--- [0;32mcompiler:3.10.1:compile[m [1m(default-compile)[m @ [36malgafood-api[0;1m ---[m
[INFO] Changes detected - recompiling the module!
[INFO] Compiling 1 source file to C:\Users\lespi\OneDrive\Área de Trabalho\sts-4.25.0.RELEASE\workspace\projeto\algaworks-especialista-rest\algafood-api\target\classes
[INFO] 
[INFO] [1m--- [0;32mresources:3.2.0:testResources[m [1m(default-testResources)[m @ [36malgafood-api[0;1m ---[m
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] Using 'UTF-8' encoding to copy filtered properties files.
[INFO] skip non existing resourceDirectory C:\Users\lespi\OneDrive\Área de Trabalho\sts-4.25.0.RELEASE\workspace\projeto\algaworks-especialista-rest\algafood-api\src\test\resources
[INFO] 
[INFO] [1m--- [0;32mcompiler:3.10.1:testCompile[m [1m(default-testCompile)[m @ [36malgafood-api[0;1m ---[m
[INFO] Changes detected - recompiling the module!
[INFO] Compiling 1 source file to C:\Users\lespi\OneDrive\Área de Trabalho\sts-4.25.0.RELEASE\workspace\projeto\algaworks-especialista-rest\algafood-api\target\test-classes
[INFO] 
[INFO] [1m--- [0;32msurefire:2.22.2:test[m [1m(default-test)[m @ [36malgafood-api[0;1m ---[m
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/maven-surefire-common/2.22.2/maven-surefire-common-2.22.2.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/maven-surefire-common/2.22.2/maven-surefire-common-2.22.2.pom (11 kB at 28 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugin-tools/maven-plugin-annotations/3.5.2/maven-plugin-annotations-3.5.2.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugin-tools/maven-plugin-annotations/3.5.2/maven-plugin-annotations-3.5.2.pom (1.6 kB at 71 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugin-tools/maven-plugin-tools/3.5.2/maven-plugin-tools-3.5.2.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugin-tools/maven-plugin-tools/3.5.2/maven-plugin-tools-3.5.2.pom (15 kB at 439 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/31/maven-parent-31.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/31/maven-parent-31.pom (43 kB at 1.2 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-api/2.22.2/surefire-api-2.22.2.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-api/2.22.2/surefire-api-2.22.2.pom (3.5 kB at 169 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-logger-api/2.22.2/surefire-logger-api-2.22.2.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-logger-api/2.22.2/surefire-logger-api-2.22.2.pom (2.0 kB at 98 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-booter/2.22.2/surefire-booter-2.22.2.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-booter/2.22.2/surefire-booter-2.22.2.pom (7.5 kB at 339 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-descriptor/2.2.1/maven-plugin-descriptor-2.2.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-descriptor/2.2.1/maven-plugin-descriptor-2.2.1.pom (2.1 kB at 98 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-project/2.2.1/maven-project-2.2.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-project/2.2.1/maven-project-2.2.1.pom (2.8 kB at 146 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings/2.2.1/maven-settings-2.2.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings/2.2.1/maven-settings-2.2.1.pom (2.2 kB at 121 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.11/plexus-interpolation-1.11.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.11/plexus-interpolation-1.11.pom (889 B at 47 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-profile/2.2.1/maven-profile-2.2.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-profile/2.2.1/maven-profile-2.2.1.pom (2.2 kB at 109 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact-manager/2.2.1/maven-artifact-manager-2.2.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact-manager/2.2.1/maven-artifact-manager-2.2.1.pom (3.1 kB at 163 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-repository-metadata/2.2.1/maven-repository-metadata-2.2.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-repository-metadata/2.2.1/maven-repository-metadata-2.2.1.pom (1.9 kB at 104 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/backport-util-concurrent/backport-util-concurrent/3.1/backport-util-concurrent-3.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/backport-util-concurrent/backport-util-concurrent/3.1/backport-util-concurrent-3.1.pom (880 B at 42 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-registry/2.2.1/maven-plugin-registry-2.2.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-registry/2.2.1/maven-plugin-registry-2.2.1.pom (1.9 kB at 92 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-core/2.2.1/maven-core-2.2.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-core/2.2.1/maven-core-2.2.1.pom (12 kB at 554 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-parameter-documenter/2.2.1/maven-plugin-parameter-documenter-2.2.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-parameter-documenter/2.2.1/maven-plugin-parameter-documenter-2.2.1.pom (2.0 kB at 103 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-jdk14/1.5.6/slf4j-jdk14-1.5.6.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-jdk14/1.5.6/slf4j-jdk14-1.5.6.pom (1.9 kB at 90 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-parent/1.5.6/slf4j-parent-1.5.6.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-parent/1.5.6/slf4j-parent-1.5.6.pom (7.9 kB at 396 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.5.6/slf4j-api-1.5.6.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.5.6/slf4j-api-1.5.6.pom (3.0 kB at 142 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/jcl-over-slf4j/1.5.6/jcl-over-slf4j-1.5.6.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/jcl-over-slf4j/1.5.6/jcl-over-slf4j-1.5.6.pom (2.2 kB at 103 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-error-diagnostics/2.2.1/maven-error-diagnostics-2.2.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-error-diagnostics/2.2.1/maven-error-diagnostics-2.2.1.pom (1.7 kB at 85 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-monitor/2.2.1/maven-monitor-2.2.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-monitor/2.2.1/maven-monitor-2.2.1.pom (1.3 kB at 63 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-toolchain/2.2.1/maven-toolchain-2.2.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-toolchain/2.2.1/maven-toolchain-2.2.1.pom (3.3 kB at 176 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-java/0.9.10/plexus-java-0.9.10.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-java/0.9.10/plexus-java-0.9.10.pom (5.1 kB at 255 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-languages/0.9.10/plexus-languages-0.9.10.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-languages/0.9.10/plexus-languages-0.9.10.pom (4.1 kB at 218 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/6.2/asm-6.2.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/6.2/asm-6.2.pom (2.9 kB at 147 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/com/thoughtworks/qdox/qdox/2.0-M8/qdox-2.0-M8.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/com/thoughtworks/qdox/qdox/2.0-M8/qdox-2.0-M8.pom (16 kB at 834 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/maven-surefire-common/2.22.2/maven-surefire-common-2.22.2.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/maven-surefire-common/2.22.2/maven-surefire-common-2.22.2.jar (528 kB at 5.3 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-api/2.2.1/maven-plugin-api-2.2.1.jar
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-booter/2.22.2/surefire-booter-2.22.2.jar
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-logger-api/2.22.2/surefire-logger-api-2.22.2.jar
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugin-tools/maven-plugin-annotations/3.5.2/maven-plugin-annotations-3.5.2.jar
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-api/2.22.2/surefire-api-2.22.2.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-api/2.2.1/maven-plugin-api-2.2.1.jar (12 kB at 476 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact/2.2.1/maven-artifact-2.2.1.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact/2.2.1/maven-artifact-2.2.1.jar (80 kB at 1.7 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/1.5.15/plexus-utils-1.5.15.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-logger-api/2.22.2/surefire-logger-api-2.22.2.jar (13 kB at 180 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-descriptor/2.2.1/maven-plugin-descriptor-2.2.1.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugin-tools/maven-plugin-annotations/3.5.2/maven-plugin-annotations-3.5.2.jar (14 kB at 183 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-project/2.2.1/maven-project-2.2.1.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/1.5.15/plexus-utils-1.5.15.jar (228 kB at 2.5 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings/2.2.1/maven-settings-2.2.1.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-descriptor/2.2.1/maven-plugin-descriptor-2.2.1.jar (39 kB at 371 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-profile/2.2.1/maven-profile-2.2.1.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-booter/2.22.2/surefire-booter-2.22.2.jar (274 kB at 2.6 MB/s)
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-api/2.22.2/surefire-api-2.22.2.jar (186 kB at 1.7 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/backport-util-concurrent/backport-util-concurrent/3.1/backport-util-concurrent-3.1.jar
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact-manager/2.2.1/maven-artifact-manager-2.2.1.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings/2.2.1/maven-settings-2.2.1.jar (49 kB at 423 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-registry/2.2.1/maven-plugin-registry-2.2.1.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-project/2.2.1/maven-project-2.2.1.jar (156 kB at 1.2 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.11/plexus-interpolation-1.11.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-profile/2.2.1/maven-profile-2.2.1.jar (35 kB at 274 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model/2.2.1/maven-model-2.2.1.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact-manager/2.2.1/maven-artifact-manager-2.2.1.jar (68 kB at 520 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-core/2.2.1/maven-core-2.2.1.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-registry/2.2.1/maven-plugin-registry-2.2.1.jar (30 kB at 211 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-parameter-documenter/2.2.1/maven-plugin-parameter-documenter-2.2.1.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.11/plexus-interpolation-1.11.jar (51 kB at 337 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-jdk14/1.5.6/slf4j-jdk14-1.5.6.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model/2.2.1/maven-model-2.2.1.jar (88 kB at 576 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.5.6/slf4j-api-1.5.6.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-parameter-documenter/2.2.1/maven-plugin-parameter-documenter-2.2.1.jar (22 kB at 138 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/jcl-over-slf4j/1.5.6/jcl-over-slf4j-1.5.6.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/backport-util-concurrent/backport-util-concurrent/3.1/backport-util-concurrent-3.1.jar (332 kB at 2.0 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/reporting/maven-reporting-api/3.0/maven-reporting-api-3.0.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.5.6/slf4j-api-1.5.6.jar (22 kB at 130 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-repository-metadata/2.2.1/maven-repository-metadata-2.2.1.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-jdk14/1.5.6/slf4j-jdk14-1.5.6.jar (8.8 kB at 51 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-error-diagnostics/2.2.1/maven-error-diagnostics-2.2.1.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-core/2.2.1/maven-core-2.2.1.jar (178 kB at 1.0 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-monitor/2.2.1/maven-monitor-2.2.1.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/jcl-over-slf4j/1.5.6/jcl-over-slf4j-1.5.6.jar (17 kB at 92 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-toolchain/2.2.1/maven-toolchain-2.2.1.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/reporting/maven-reporting-api/3.0/maven-reporting-api-3.0.jar (11 kB at 60 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-java/0.9.10/plexus-java-0.9.10.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-error-diagnostics/2.2.1/maven-error-diagnostics-2.2.1.jar (13 kB at 64 kB/s)
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-repository-metadata/2.2.1/maven-repository-metadata-2.2.1.jar (26 kB at 127 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/6.2/asm-6.2.jar
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/com/thoughtworks/qdox/qdox/2.0-M8/qdox-2.0-M8.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-monitor/2.2.1/maven-monitor-2.2.1.jar (10 kB at 51 kB/s)
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-toolchain/2.2.1/maven-toolchain-2.2.1.jar (38 kB at 183 kB/s)
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-java/0.9.10/plexus-java-0.9.10.jar (39 kB at 186 kB/s)
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/6.2/asm-6.2.jar (111 kB at 481 kB/s)
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/com/thoughtworks/qdox/qdox/2.0-M8/qdox-2.0-M8.jar (316 kB at 1.2 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-junit-platform/2.22.2/surefire-junit-platform-2.22.2.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-junit-platform/2.22.2/surefire-junit-platform-2.22.2.pom (7.0 kB at 367 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-providers/2.22.2/surefire-providers-2.22.2.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-providers/2.22.2/surefire-providers-2.22.2.pom (2.5 kB at 131 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-launcher/1.3.1/junit-platform-launcher-1.3.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-launcher/1.3.1/junit-platform-launcher-1.3.1.pom (2.2 kB at 111 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apiguardian/apiguardian-api/1.0.0/apiguardian-api-1.0.0.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apiguardian/apiguardian-api/1.0.0/apiguardian-api-1.0.0.pom (1.2 kB at 61 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-engine/1.3.1/junit-platform-engine-1.3.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-engine/1.3.1/junit-platform-engine-1.3.1.pom (2.4 kB at 120 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-commons/1.3.1/junit-platform-commons-1.3.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-commons/1.3.1/junit-platform-commons-1.3.1.pom (2.0 kB at 112 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/opentest4j/opentest4j/1.1.1/opentest4j-1.1.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/opentest4j/opentest4j/1.1.1/opentest4j-1.1.1.pom (1.7 kB at 94 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-junit-platform/2.22.2/surefire-junit-platform-2.22.2.jar
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-commons/1.3.1/junit-platform-commons-1.3.1.jar
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-launcher/1.3.1/junit-platform-launcher-1.3.1.jar
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apiguardian/apiguardian-api/1.0.0/apiguardian-api-1.0.0.jar
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-engine/1.3.1/junit-platform-engine-1.3.1.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apiguardian/apiguardian-api/1.0.0/apiguardian-api-1.0.0.jar (2.2 kB at 90 kB/s)
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-junit-platform/2.22.2/surefire-junit-platform-2.22.2.jar (66 kB at 2.5 MB/s)
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-launcher/1.3.1/junit-platform-launcher-1.3.1.jar (95 kB at 3.6 MB/s)
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-commons/1.3.1/junit-platform-commons-1.3.1.jar (78 kB at 2.6 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/opentest4j/opentest4j/1.1.1/opentest4j-1.1.1.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-engine/1.3.1/junit-platform-engine-1.3.1.jar (135 kB at 3.6 MB/s)
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/opentest4j/opentest4j/1.1.1/opentest4j-1.1.1.jar (7.1 kB at 356 kB/s)
[INFO] 
[INFO] -------------------------------------------------------
[INFO]  T E S T S
[INFO] -------------------------------------------------------
[INFO] Running com.algaworks.algafood.[1mAlgafoodApiApplicationTests[m
14:00:30.644 [main] DEBUG org.springframework.test.context.BootstrapUtils - Instantiating CacheAwareContextLoaderDelegate from class [org.springframework.test.context.cache.DefaultCacheAwareContextLoaderDelegate]
14:00:30.668 [main] DEBUG org.springframework.test.context.BootstrapUtils - Instantiating BootstrapContext using constructor [public org.springframework.test.context.support.DefaultBootstrapContext(java.lang.Class,org.springframework.test.context.CacheAwareContextLoaderDelegate)]
14:00:30.716 [main] DEBUG org.springframework.test.context.BootstrapUtils - Instantiating TestContextBootstrapper for test class [com.algaworks.algafood.AlgafoodApiApplicationTests] from class [org.springframework.boot.test.context.SpringBootTestContextBootstrapper]
14:00:30.730 [main] INFO org.springframework.boot.test.context.SpringBootTestContextBootstrapper - Neither @ContextConfiguration nor @ContextHierarchy found for test class [com.algaworks.algafood.AlgafoodApiApplicationTests], using SpringBootContextLoader
14:00:30.734 [main] DEBUG org.springframework.test.context.support.AbstractContextLoader - Did not detect default resource location for test class [com.algaworks.algafood.AlgafoodApiApplicationTests]: class path resource [com/algaworks/algafood/AlgafoodApiApplicationTests-context.xml] does not exist
14:00:30.735 [main] DEBUG org.springframework.test.context.support.AbstractContextLoader - Did not detect default resource location for test class [com.algaworks.algafood.AlgafoodApiApplicationTests]: class path resource [com/algaworks/algafood/AlgafoodApiApplicationTestsContext.groovy] does not exist
14:00:30.735 [main] INFO org.springframework.test.context.support.AbstractContextLoader - Could not detect default resource locations for test class [com.algaworks.algafood.AlgafoodApiApplicationTests]: no resource found for suffixes {-context.xml, Context.groovy}.
14:00:30.736 [main] INFO org.springframework.test.context.support.AnnotationConfigContextLoaderUtils - Could not detect default configuration classes for test class [com.algaworks.algafood.AlgafoodApiApplicationTests]: AlgafoodApiApplicationTests does not declare any static, non-private, non-final, nested classes annotated with @Configuration.
14:00:30.796 [main] DEBUG org.springframework.test.context.support.ActiveProfilesUtils - Could not find an 'annotation declaring class' for annotation type [org.springframework.test.context.ActiveProfiles] and class [com.algaworks.algafood.AlgafoodApiApplicationTests]
14:00:30.873 [main] DEBUG org.springframework.context.annotation.ClassPathScanningCandidateComponentProvider - Identified candidate component class: file [C:\Users\lespi\OneDrive\Área de Trabalho\sts-4.25.0.RELEASE\workspace\projeto\algaworks-especialista-rest\algafood-api\target\classes\com\algaworks\algafood\AlgafoodApiApplication.class]
14:00:30.874 [main] INFO org.springframework.boot.test.context.SpringBootTestContextBootstrapper - Found @SpringBootConfiguration com.algaworks.algafood.AlgafoodApiApplication for test class com.algaworks.algafood.AlgafoodApiApplicationTests
14:00:31.017 [main] DEBUG org.springframework.boot.test.context.SpringBootTestContextBootstrapper - @TestExecutionListeners is not present for class [com.algaworks.algafood.AlgafoodApiApplicationTests]: using defaults.
14:00:31.018 [main] INFO org.springframework.boot.test.context.SpringBootTestContextBootstrapper - Loaded default TestExecutionListener class names from location [META-INF/spring.factories]: [org.springframework.boot.test.mock.mockito.MockitoTestExecutionListener, org.springframework.boot.test.mock.mockito.ResetMocksTestExecutionListener, org.springframework.boot.test.autoconfigure.restdocs.RestDocsTestExecutionListener, org.springframework.boot.test.autoconfigure.web.client.MockRestServiceServerResetTestExecutionListener, org.springframework.boot.test.autoconfigure.web.servlet.MockMvcPrintOnlyOnFailureTestExecutionListener, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverTestExecutionListener, org.springframework.boot.test.autoconfigure.webservices.client.MockWebServiceServerTestExecutionListener, org.springframework.test.context.web.ServletTestExecutionListener, org.springframework.test.context.support.DirtiesContextBeforeModesTestExecutionListener, org.springframework.test.context.event.ApplicationEventsTestExecutionListener, org.springframework.test.context.support.DependencyInjectionTestExecutionListener, org.springframework.test.context.support.DirtiesContextTestExecutionListener, org.springframework.test.context.transaction.TransactionalTestExecutionListener, org.springframework.test.context.jdbc.SqlScriptsTestExecutionListener, org.springframework.test.context.event.EventPublishingTestExecutionListener]
14:00:31.035 [main] DEBUG org.springframework.boot.test.context.SpringBootTestContextBootstrapper - Skipping candidate TestExecutionListener [org.springframework.test.context.transaction.TransactionalTestExecutionListener] due to a missing dependency. Specify custom listener classes or make the default listener classes and their required dependencies available. Offending class: [org/springframework/transaction/interceptor/TransactionAttributeSource]
14:00:31.035 [main] DEBUG org.springframework.boot.test.context.SpringBootTestContextBootstrapper - Skipping candidate TestExecutionListener [org.springframework.test.context.jdbc.SqlScriptsTestExecutionListener] due to a missing dependency. Specify custom listener classes or make the default listener classes and their required dependencies available. Offending class: [org/springframework/transaction/interceptor/TransactionAttribute]
14:00:31.035 [main] INFO org.springframework.boot.test.context.SpringBootTestContextBootstrapper - Using TestExecutionListeners: [org.springframework.test.context.web.ServletTestExecutionListener@5f7b97da, org.springframework.test.context.support.DirtiesContextBeforeModesTestExecutionListener@18b0930f, org.springframework.test.context.event.ApplicationEventsTestExecutionListener@6b7906b3, org.springframework.boot.test.mock.mockito.MockitoTestExecutionListener@3a1dd365, org.springframework.boot.test.autoconfigure.SpringBootDependencyInjectionTestExecutionListener@395b56bb, org.springframework.test.context.support.DirtiesContextTestExecutionListener@256f8274, org.springframework.test.context.event.EventPublishingTestExecutionListener@68044f4, org.springframework.boot.test.mock.mockito.ResetMocksTestExecutionListener@52d239ba, org.springframework.boot.test.autoconfigure.restdocs.RestDocsTestExecutionListener@315f43d5, org.springframework.boot.test.autoconfigure.web.client.MockRestServiceServerResetTestExecutionListener@68fa0ba8, org.springframework.boot.test.autoconfigure.web.servlet.MockMvcPrintOnlyOnFailureTestExecutionListener@6c5945a7, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverTestExecutionListener@2f05be7f, org.springframework.boot.test.autoconfigure.webservices.client.MockWebServiceServerTestExecutionListener@640f11a1]
14:00:31.041 [main] DEBUG org.springframework.test.context.support.AbstractDirtiesContextTestExecutionListener - Before test class: context [DefaultTestContext@5a411614 testClass = AlgafoodApiApplicationTests, testInstance = [null], testMethod = [null], testException = [null], mergedContextConfiguration = [WebMergedContextConfiguration@2374d36a testClass = AlgafoodApiApplicationTests, locations = '{}', classes = '{class com.algaworks.algafood.AlgafoodApiApplication}', contextInitializerClasses = '[]', activeProfiles = '{}', propertySourceLocations = '{}', propertySourceProperties = '{org.springframework.boot.test.context.SpringBootTestContextBootstrapper=true}', contextCustomizers = set[org.springframework.boot.test.context.filter.ExcludeFilterContextCustomizer@7bf3a5d8, org.springframework.boot.test.json.DuplicateJsonObjectContextCustomizerFactory$DuplicateJsonObjectContextCustomizer@72ef8d15, org.springframework.boot.test.mock.mockito.MockitoContextCustomizer@0, org.springframework.boot.test.web.client.TestRestTemplateContextCustomizer@6ea2bc93, org.springframework.boot.test.autoconfigure.actuate.metrics.MetricsExportContextCustomizerFactory$DisableMetricExportContextCustomizer@5f77d0f9, org.springframework.boot.test.autoconfigure.properties.PropertyMappingContextCustomizer@0, org.springframework.boot.test.autoconfigure.web.servlet.WebDriverContextCustomizerFactory$Customizer@420a85c4, org.springframework.boot.test.context.SpringBootTestArgs@1, org.springframework.boot.test.context.SpringBootTestWebEnvironment@6dc17b83], resourceBasePath = 'src/main/webapp', contextLoader = 'org.springframework.boot.test.context.SpringBootContextLoader', parent = [null]], attributes = map['org.springframework.test.context.web.ServletTestExecutionListener.activateListener' -> true]], class annotated with @DirtiesContext [false] with mode [null].

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::               (v2.7.18)

2024-09-24 14:00:31.517  INFO 5816 --- [           main] c.a.a.AlgafoodApiApplicationTests        : Starting AlgafoodApiApplicationTests using Java 21.0.4 on lesp with PID 5816 (started by lesp in C:\Users\lespi\OneDrive\Área de Trabalho\sts-4.25.0.RELEASE\workspace\projeto\algaworks-especialista-rest\algafood-api)
2024-09-24 14:00:31.520  INFO 5816 --- [           main] c.a.a.AlgafoodApiApplicationTests        : No active profile set, falling back to 1 default profile: "default"
2024-09-24 14:00:33.344  INFO 5816 --- [           main] c.a.a.AlgafoodApiApplicationTests        : Started AlgafoodApiApplicationTests in 2.251 seconds (JVM running for 4.182)
[INFO] [1;32mTests run: [0;1;32m1[m, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 3.08 s - in com.algaworks.algafood.[1mAlgafoodApiApplicationTests[m
[INFO] 
[INFO] Results:
[INFO] 
[INFO] [1;32mTests run: 1, Failures: 0, Errors: 0, Skipped: 0[m
[INFO] 
[INFO] 
[INFO] [1m--- [0;32mjar:3.2.2:jar[m [1m(default-jar)[m @ [36malgafood-api[0;1m ---[m
[INFO] Building jar: C:\Users\lespi\OneDrive\Área de Trabalho\sts-4.25.0.RELEASE\workspace\projeto\algaworks-especialista-rest\algafood-api\target\algafood-api-0.0.1-SNAPSHOT.jar
[INFO] 
[INFO] [1m--- [0;32mspring-boot:2.7.18:repackage[m [1m(repackage)[m @ [36malgafood-api[0;1m ---[m
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-buildpack-platform/2.7.18/spring-boot-buildpack-platform-2.7.18.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-buildpack-platform/2.7.18/spring-boot-buildpack-platform-2.7.18.pom (3.4 kB at 121 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna-platform/5.7.0/jna-platform-5.7.0.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna-platform/5.7.0/jna-platform-5.7.0.pom (1.8 kB at 95 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna/5.7.0/jna-5.7.0.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna/5.7.0/jna-5.7.0.pom (1.6 kB at 75 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpclient/4.5.14/httpclient-4.5.14.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpclient/4.5.14/httpclient-4.5.14.pom (6.6 kB at 368 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpcomponents-client/4.5.14/httpcomponents-client-4.5.14.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpcomponents-client/4.5.14/httpcomponents-client-4.5.14.pom (15 kB at 849 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpcore/4.4.16/httpcore-4.4.16.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpcore/4.4.16/httpcore-4.4.16.pom (5.0 kB at 292 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpcomponents-core/4.4.16/httpcomponents-core-4.4.16.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpcomponents-core/4.4.16/httpcomponents-core-4.4.16.pom (12 kB at 703 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/tomlj/tomlj/1.0.0/tomlj-1.0.0.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/tomlj/tomlj/1.0.0/tomlj-1.0.0.pom (2.8 kB at 149 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/antlr/antlr4-runtime/4.7.2/antlr4-runtime-4.7.2.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/antlr/antlr4-runtime/4.7.2/antlr4-runtime-4.7.2.pom (3.6 kB at 201 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/antlr/antlr4-master/4.7.2/antlr4-master-4.7.2.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/antlr/antlr4-master/4.7.2/antlr4-master-4.7.2.pom (4.4 kB at 245 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/com/google/code/findbugs/jsr305/3.0.2/jsr305-3.0.2.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/com/google/code/findbugs/jsr305/3.0.2/jsr305-3.0.2.pom (4.3 kB at 238 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-loader-tools/2.7.18/spring-boot-loader-tools-2.7.18.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-loader-tools/2.7.18/spring-boot-loader-tools-2.7.18.pom (2.2 kB at 118 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-shade-plugin/3.2.4/maven-shade-plugin-3.2.4.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-shade-plugin/3.2.4/maven-shade-plugin-3.2.4.pom (11 kB at 538 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-component-annotations/1.5.4/plexus-component-annotations-1.5.4.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-component-annotations/1.5.4/plexus-component-annotations-1.5.4.pom (815 B at 45 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-containers/1.5.4/plexus-containers-1.5.4.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-containers/1.5.4/plexus-containers-1.5.4.pom (4.2 kB at 202 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/2.0.5/plexus-2.0.5.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/2.0.5/plexus-2.0.5.pom (17 kB at 1.1 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-artifact-transfer/0.12.0/maven-artifact-transfer-0.12.0.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-artifact-transfer/0.12.0/maven-artifact-transfer-0.12.0.pom (11 kB at 592 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/33/maven-shared-components-33.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/33/maven-shared-components-33.pom (5.1 kB at 340 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-component-annotations/1.7.1/plexus-component-annotations-1.7.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-component-annotations/1.7.1/plexus-component-annotations-1.7.1.pom (770 B at 45 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-containers/1.7.1/plexus-containers-1.7.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-containers/1.7.1/plexus-containers-1.7.1.pom (5.0 kB at 314 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.0.1/maven-common-artifact-filters-3.0.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.0.1/maven-common-artifact-filters-3.0.1.pom (4.8 kB at 284 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/30/maven-shared-components-30.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/30/maven-shared-components-30.pom (4.6 kB at 286 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/30/maven-parent-30.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/30/maven-parent-30.pom (41 kB at 2.3 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/3.1.0/maven-shared-utils-3.1.0.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/3.1.0/maven-shared-utils-3.1.0.pom (5.0 kB at 277 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.1.1/plexus-utils-3.1.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/3.1.1/plexus-utils-3.1.1.pom (5.1 kB at 282 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/8.0/asm-8.0.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/8.0/asm-8.0.pom (2.9 kB at 164 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-commons/8.0/asm-commons-8.0.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-commons/8.0/asm-commons-8.0.pom (3.7 kB at 193 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-tree/8.0/asm-tree-8.0.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-tree/8.0/asm-tree-8.0.pom (3.1 kB at 174 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-analysis/8.0/asm-analysis-8.0.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-analysis/8.0/asm-analysis-8.0.pom (3.2 kB at 166 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/jdom/jdom2/2.0.6/jdom2-2.0.6.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/jdom/jdom2/2.0.6/jdom2-2.0.6.pom (4.6 kB at 242 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-dependency-tree/3.0.1/maven-dependency-tree-3.0.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-dependency-tree/3.0.1/maven-dependency-tree-3.0.1.pom (7.5 kB at 416 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-component-annotations/1.6/plexus-component-annotations-1.6.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-component-annotations/1.6/plexus-component-annotations-1.6.pom (748 B at 47 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-containers/1.6/plexus-containers-1.6.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-containers/1.6/plexus-containers-1.6.pom (3.8 kB at 222 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/3.3.2/plexus-3.3.2.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/3.3.2/plexus-3.3.2.pom (22 kB at 1.3 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/vafer/jdependency/2.4.0/jdependency-2.4.0.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/vafer/jdependency/2.4.0/jdependency-2.4.0.pom (15 kB at 793 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-util/8.0/asm-util-8.0.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-util/8.0/asm-util-8.0.pom (3.7 kB at 192 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/com/google/guava/guava/28.2-android/guava-28.2-android.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/com/google/guava/guava/28.2-android/guava-28.2-android.pom (11 kB at 607 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/com/google/guava/guava-parent/28.2-android/guava-parent-28.2-android.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/com/google/guava/guava-parent/28.2-android/guava-parent-28.2-android.pom (13 kB at 679 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/com/google/guava/failureaccess/1.0.1/failureaccess-1.0.1.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/com/google/guava/failureaccess/1.0.1/failureaccess-1.0.1.pom (2.4 kB at 134 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/com/google/guava/guava-parent/26.0-android/guava-parent-26.0-android.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/com/google/guava/guava-parent/26.0-android/guava-parent-26.0-android.pom (10 kB at 536 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/com/google/guava/listenablefuture/9999.0-empty-to-avoid-conflict-with-guava/listenablefuture-9999.0-empty-to-avoid-conflict-with-guava.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/com/google/guava/listenablefuture/9999.0-empty-to-avoid-conflict-with-guava/listenablefuture-9999.0-empty-to-avoid-conflict-with-guava.pom (2.3 kB at 120 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/checkerframework/checker-compat-qual/2.5.5/checker-compat-qual-2.5.5.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/checkerframework/checker-compat-qual/2.5.5/checker-compat-qual-2.5.5.pom (2.7 kB at 137 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/com/google/errorprone/error_prone_annotations/2.3.4/error_prone_annotations-2.3.4.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/com/google/errorprone/error_prone_annotations/2.3.4/error_prone_annotations-2.3.4.pom (2.1 kB at 117 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/com/google/errorprone/error_prone_parent/2.3.4/error_prone_parent-2.3.4.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/com/google/errorprone/error_prone_parent/2.3.4/error_prone_parent-2.3.4.pom (5.4 kB at 285 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/com/google/j2objc/j2objc-annotations/1.3/j2objc-annotations-1.3.pom
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/com/google/j2objc/j2objc-annotations/1.3/j2objc-annotations-1.3.pom (2.8 kB at 145 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-buildpack-platform/2.7.18/spring-boot-buildpack-platform-2.7.18.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-buildpack-platform/2.7.18/spring-boot-buildpack-platform-2.7.18.jar (264 kB at 6.0 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna-platform/5.7.0/jna-platform-5.7.0.jar
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna/5.7.0/jna-5.7.0.jar
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.21/commons-compress-1.21.jar
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpclient/4.5.14/httpclient-4.5.14.jar
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpcore/4.4.16/httpcore-4.4.16.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpclient/4.5.14/httpclient-4.5.14.jar (786 kB at 19 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/tomlj/tomlj/1.0.0/tomlj-1.0.0.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpcore/4.4.16/httpcore-4.4.16.jar (328 kB at 6.0 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/antlr/antlr4-runtime/4.7.2/antlr4-runtime-4.7.2.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/tomlj/tomlj/1.0.0/tomlj-1.0.0.jar (157 kB at 2.5 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/com/google/code/findbugs/jsr305/3.0.2/jsr305-3.0.2.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/com/google/code/findbugs/jsr305/3.0.2/jsr305-3.0.2.jar (20 kB at 243 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-loader-tools/2.7.18/spring-boot-loader-tools-2.7.18.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/antlr/antlr4-runtime/4.7.2/antlr4-runtime-4.7.2.jar (338 kB at 3.2 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/1.5.8/plexus-utils-1.5.8.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.21/commons-compress-1.21.jar (1.0 MB at 9.6 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-shade-plugin/3.2.4/maven-shade-plugin-3.2.4.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-loader-tools/2.7.18/spring-boot-loader-tools-2.7.18.jar (250 kB at 2.3 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-api/3.0/maven-plugin-api-3.0.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/1.5.8/plexus-utils-1.5.8.jar (268 kB at 2.0 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model/3.0/maven-model-3.0.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-plugin-api/3.0/maven-plugin-api-3.0.jar (49 kB at 371 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-core/3.0/maven-core-3.0.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-shade-plugin/3.2.4/maven-shade-plugin-3.2.4.jar (134 kB at 981 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings/3.0/maven-settings-3.0.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna/5.7.0/jna-5.7.0.jar (1.7 MB at 12 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings-builder/3.0/maven-settings-builder-3.0.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna-platform/5.7.0/jna-platform-5.7.0.jar (1.3 MB at 9.0 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-repository-metadata/3.0/maven-repository-metadata-3.0.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings/3.0/maven-settings-3.0.jar (47 kB at 297 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model-builder/3.0/maven-model-builder-3.0.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model/3.0/maven-model-3.0.jar (165 kB at 1.0 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-aether-provider/3.0/maven-aether-provider-3.0.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-settings-builder/3.0/maven-settings-builder-3.0.jar (38 kB at 226 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-impl/1.7/aether-impl-1.7.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-repository-metadata/3.0/maven-repository-metadata-3.0.jar (30 kB at 180 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-spi/1.7/aether-spi-1.7.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-aether-provider/3.0/maven-aether-provider-3.0.jar (51 kB at 278 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-api/1.7/aether-api-1.7.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-model-builder/3.0/maven-model-builder-3.0.jar (148 kB at 796 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-util/1.7/aether-util-1.7.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-spi/1.7/aether-spi-1.7.jar (14 kB at 72 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.14/plexus-interpolation-1.14.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-core/3.0/maven-core-3.0.jar (527 kB at 2.8 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-classworlds/2.2.3/plexus-classworlds-2.2.3.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-impl/1.7/aether-impl-1.7.jar (106 kB at 554 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact/3.0/maven-artifact-3.0.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-api/1.7/aether-api-1.7.jar (74 kB at 362 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-artifact-transfer/0.12.0/maven-artifact-transfer-0.12.0.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.14/plexus-interpolation-1.14.jar (61 kB at 289 kB/s)
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/sonatype/aether/aether-util/1.7/aether-util-1.7.jar (108 kB at 512 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.0.1/maven-common-artifact-filters-3.0.1.jar
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/3.1.0/maven-shared-utils-3.1.0.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-classworlds/2.2.3/plexus-classworlds-2.2.3.jar (46 kB at 216 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.7.5/slf4j-api-1.7.5.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-artifact/3.0/maven-artifact-3.0.jar (52 kB at 235 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/8.0/asm-8.0.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-artifact-transfer/0.12.0/maven-artifact-transfer-0.12.0.jar (120 kB at 519 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-commons/8.0/asm-commons-8.0.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.0.1/maven-common-artifact-filters-3.0.1.jar (61 kB at 257 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-tree/8.0/asm-tree-8.0.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.7.5/slf4j-api-1.7.5.jar (26 kB at 107 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-analysis/8.0/asm-analysis-8.0.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/8.0/asm-8.0.jar (122 kB at 493 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/jdom/jdom2/2.0.6/jdom2-2.0.6.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-utils/3.1.0/maven-shared-utils-3.1.0.jar (164 kB at 660 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-dependency-tree/3.0.1/maven-dependency-tree-3.0.1.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-commons/8.0/asm-commons-8.0.jar (72 kB at 281 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/vafer/jdependency/2.4.0/jdependency-2.4.0.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-tree/8.0/asm-tree-8.0.jar (53 kB at 199 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-util/8.0/asm-util-8.0.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-analysis/8.0/asm-analysis-8.0.jar (33 kB at 127 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/com/google/guava/guava/28.2-android/guava-28.2-android.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-dependency-tree/3.0.1/maven-dependency-tree-3.0.1.jar (37 kB at 137 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/com/google/guava/failureaccess/1.0.1/failureaccess-1.0.1.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/jdom/jdom2/2.0.6/jdom2-2.0.6.jar (305 kB at 1.1 MB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/com/google/guava/listenablefuture/9999.0-empty-to-avoid-conflict-with-guava/listenablefuture-9999.0-empty-to-avoid-conflict-with-guava.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/vafer/jdependency/2.4.0/jdependency-2.4.0.jar (180 kB at 632 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/checkerframework/checker-compat-qual/2.5.5/checker-compat-qual-2.5.5.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-util/8.0/asm-util-8.0.jar (85 kB at 296 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/com/google/errorprone/error_prone_annotations/2.3.4/error_prone_annotations-2.3.4.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/com/google/guava/failureaccess/1.0.1/failureaccess-1.0.1.jar (4.6 kB at 16 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/com/google/j2objc/j2objc-annotations/1.3/j2objc-annotations-1.3.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/com/google/guava/listenablefuture/9999.0-empty-to-avoid-conflict-with-guava/listenablefuture-9999.0-empty-to-avoid-conflict-with-guava.jar (2.2 kB at 7.5 kB/s)
[INFO] Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.7/commons-lang3-3.7.jar
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/checkerframework/checker-compat-qual/2.5.5/checker-compat-qual-2.5.5.jar (5.9 kB at 19 kB/s)
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/com/google/errorprone/error_prone_annotations/2.3.4/error_prone_annotations-2.3.4.jar (14 kB at 45 kB/s)
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/com/google/j2objc/j2objc-annotations/1.3/j2objc-annotations-1.3.jar (8.8 kB at 29 kB/s)
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.7/commons-lang3-3.7.jar (500 kB at 1.5 MB/s)
[INFO] Downloaded from central: https://repo.maven.apache.org/maven2/com/google/guava/guava/28.2-android/guava-28.2-android.jar (2.6 MB at 6.6 MB/s)
[INFO] Replacing main artifact with repackaged archive
[INFO] [1m------------------------------------------------------------------------[m
[INFO] [1;32mBUILD SUCCESS[m
[INFO] [1m------------------------------------------------------------------------[m
[INFO] Total time:  13.559 s
[INFO] Finished at: 2024-09-24T14:00:36-03:00
[INFO] [1m------------------------------------------------------------------------[m
[WARNING] The requested profile "pom.xml" could not be activated because it does not exist.

```

# Rodar o projeto com o Maven

```sh
java -jar .\target\algafood-api-0.0.1-SNAPSHOT.jar


  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::               (v2.7.18)

2024-09-24 14:20:31.588  INFO 12748 --- [           main] c.a.algafood.AlgafoodApiApplication      : Starting AlgafoodApiApplication v0.0.1-SNAPSHOT using Java 21.0.4 on lesp with PID 12748 (C:\Users\lespi\OneDrive\├ürea de Trabalho\sts-4.25.0.RELEASE\workspace\projeto\algaworks-especialista-rest\algafood-api\target\algafood-api-0.0.1-SNAPSHOT.jar started by lesp in C:\Users\lespi\OneDrive\├ürea de Trabalho\sts-4.25.0.RELEASE\workspace\projeto\algaworks-especialista-rest\algafood-api)
2024-09-24 14:20:31.592  INFO 12748 --- [           main] c.a.algafood.AlgafoodApiApplication      : No active profile set, falling back to 1 default profile: "default"
2024-09-24 14:20:32.948  INFO 12748 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 8080 (http)
2024-09-24 14:20:32.966  INFO 12748 --- [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2024-09-24 14:20:32.967  INFO 12748 --- [           main] org.apache.catalina.core.StandardEngine  : Starting Servlet engine: [Apache Tomcat/9.0.83]
2024-09-24 14:20:33.154  INFO 12748 --- [           main] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext

2024-09-24 14:20:33.697  INFO 12748 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port(s): 8080 (http) with context path ''
2024-09-24 14:20:33.709  INFO 12748 --- [           main] c.a.algafood.AlgafoodApiApplication      : Started AlgafoodApiApplication in 2.833 seconds (JVM running for 3.47
```

![alt text](image-57.png)

```sh
.\mvnw clean
[INFO] Scanning for projects...
[INFO]
[INFO] ---------------------< com.algaworks:algafood-api >---------------------
[INFO] Building algafood-api 0.0.1-SNAPSHOT
[INFO]   from pom.xml
[INFO] --------------------------------[ jar ]---------------------------------
[INFO]
[INFO] --- clean:3.2.0:clean (default-clean) @ algafood-api ---
[INFO] Deleting C:\Users\lespi\OneDrive\Área de Trabalho\sts-4.25.0.RELEASE\workspace\projeto\algaworks-especialista-rest\algafood-api\target
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  0.653 s
[INFO] Finished at: 2024-09-24T14:22:31-03:00
[INFO] ------------------------------------------------------------------------
```