# Update-to-linux-debian-
apt-get upgrade Reading package lists... Done Building dependency tree        Reading state information... Done The following packages will be upgraded:   acpid at base-files clive deb-multimedia-keyring debian-multimedia-keyring evolution-data-server evolution-data-server-common firmware-linux-free   foomatic-filters gir1.0-json-glib-1.0 iceweasel libapr1 libavutil49 libbrlapi0.5 libcamel1.2-14 libebackend1.2-0 libebook1.2-9 libecal1.2-7   libedata-book1.2-2 libedata-cal1.2-7 libedataserver1.2-13 libedataserverui1.2-8 libegroupwise1.2-13 libgdata-google1.2-1 libgdata1.2-1 libjson-glib-1.0-0   libmozjs2d libpolkit-agent-1-0 libpolkit-backend-1-0 libpolkit-gobject-1-0 libssl0.9.8 libxi6 linux-base linux-headers-2.6.32-5-686   linux-headers-2.6.32-5-common linux-image-2.6.32-5-486 linux-image-2.6.32-5-686 locales openssh-client openssl policykit-1 procps python-brlapi sysvinit   tzdata xulrunner-1.9.1 47 upgraded, 0 newly installed, 0 to remove and 0 not upgraded. 8 not fully installed or removed. Need to get 2736 B/85.7 MB of archives. After this operation, 426 kB of additional disk space will be used. Do you want to continue [Y/n]? Get:1 ftp://ftp.debian-multimedia.org/ squeeze/main debian-multimedia-keyring all 2010.12.26-4 [2736 B] Fetched 2736 B in 0s (4015 B/s)                Traceback (most recent call last):   File "/usr/bin/apt-listchanges", line 33, in &lt;module>     from ALChacks import *   File "/usr/share/apt-listchanges/ALChacks.py", line 32, in &lt;module>     sys.stderr.write(_("Can't set locale; make sure $LC_* and $LANG are correct!\n")) NameError: name '_' is not defined perl: warning: Setting locale failed. perl: warning: Please check that your locale settings:    LANGUAGE = (unset),    LC_ALL = (unset),    LANG = "c"     are supported and installed on your system. perl: warning: Falling back to the standard locale ("C"). locale: Cannot set LC_CTYPE to default locale: No such file or directory locale: Cannot set LC_MESSAGES to default locale: No such file or directory locale: Cannot set LC_ALL to default locale: No such file or directory Extracting templates from packages: 100% Preconfiguring packages ... perl: warning: Setting locale failed. perl: warning: Please check that your locale settings:    LANGUAGE = (unset),    LC_ALL = (unset),    LANG = "c"     are supported and installed on your system. perl: warning: Falling back to the standard locale ("C"). Setting up initscripts (2.88dsf-13.1+squeeze1) ... insserv: warning: script 'S99pcloudd_init' missing LSB tags and overrides insserv: warning: script 'pcloudd_init' missing LSB tags and overrides insserv: script pcloudd_init: service pcloudd_init already provided! insserv: warning: script 'pcloudd_init_start' missing LSB tags and overrides insserv: There is a loop at service mediatomb if started insserv: There is a loop between service pcloudd_init and mountnfs-bootclean if started insserv:  loop involving service mountnfs-bootclean at depth 9 insserv:  loop involving service mountnfs at depth 8 insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Max recursions depth 99 reached insserv:  loop involving service nfs-common at depth 7 insserv: There is a loop between service mediatomb and checkroot if started insserv:  loop involving service checkroot at depth 5 insserv:  loop involving service hostname at depth 4 insserv:  loop involving service alsa-utils at depth 12 insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: There is a loop between service pcloudd_init and mountnfs if started insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv:  loop involving service rsyslog at depth 12 insserv: There is a loop between service mediatomb and ifupdown if started insserv:  loop involving service ifupdown at depth 7 insserv:  loop involving service ifupdown-clean at depth 6 insserv: There is a loop between service pcloudd_init and bootlogd if started insserv:  loop involving service bootlogd at depth 3 insserv:  loop involving service mountdevsubfs at depth 2 insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: There is a loop between service mediatomb and mountall if started insserv:  loop involving service mountall at depth 8 insserv:  loop involving service checkfs at depth 7 insserv:  loop involving service mtab at depth 6 insserv: There is a loop at service pcloudd_init if started insserv:  loop involving service module-init-tools at depth 6 insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends oconfigured to not write apport reports                                                                                     n mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: There is a loop between service mediatomb and pcloudd_init_start if stopped insserv:  loop involving service pcloudd_init_start at depth 2 insserv:  loop involving service mediatomb at depth 1 insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: There is a loop between service mediatomb and ifupdown-clean if started insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: There is a loop between service mediatomb and mountall-bootclean if started insserv:  loop involving service mountall-bootclean at depth 1 insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv:  loop involving service networking at depth 10 insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Starting pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: Stopping pcloudd_init_start depends on mediatomb and therefore on system facility `$all' which can not be true! insserv: exiting now without changing boot order! update-rc.d: error: insserv rejected the script header dpkg: error processing initscripts (--configure):  subprocess installed post-installation script returned error exit status 1 Errors were encountered while processing:  initscripts



No stable repozitorii
# dpkg --purge mediatomb
