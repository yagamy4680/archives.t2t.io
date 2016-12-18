2015-10-09 - v4.1.10-ti-r21 kernel
2015-09-11 - v4.1.6-ti-r15 kernel
2015-08-17 - v4.1.5-ti-r10 kernel
2016-02-11 - v4.1.17-ti-rt-r47 kernel


ubuntu-14.04-console-armhf-2014-08-13-apps-1400mb.bin.xz
	- base
		- ubuntu-14.04-console-armhf-2014-08-13.zip
	- installed-packages
		- wireless-tools
		- iw
		- wpasupplicant
		- gawk
		- sysstat
		- jq
		- httpie
		- virt-what
		- socat
		- screen
		- xz-utils
		- vim
		- htop
		- build-essential
		- telnet
		- libbluetooth-dev


ubuntu-14.04-console-armhf-2014-08-13-apps-1400mb-v2.bin.xz
	- date
		- 2016/3/16
	- base
		- ubuntu-14.04-console-armhf-2014-08-13-apps-1000mb.bin.xz
	- installed packages (extras)
		- python3-pip
	- installed python3 packages
		- psutils
	- installed nodejs runtimes (via nodenv)
		- 4.4.0 (default)
		- 4.3.2
		- 5.7.1
	- installed components
		- /opt/dotfiles (from https://github.com/yagamy4680/dotfiles)
		- /root/.nodenv
		- /root/.vim
	- generated files
		- /opt/system
			OS_KERNEL       linux
			OS_DIST_NAME    ubuntu
			OS_DIST_CODENAME        trusty
			OS_ARCH x86_64
			OS_NAME linux-ubuntu-trusty


ubuntu-14.04.3-console-armhf-2016-02-11-raw-1700mb.img.xz
	- date
		- 2016/4/26
	- base
		- bone-ubuntu-14.04.3-console-armhf-2016-02-11-2gb.img.xz
	- installed packages (extras)
		- python3-pip
	- installed python3 packages
		- psutils
	- installed nodejs runtimes (via nodenv)
		- 4.4.0 (default)
		- 4.3.2
		- 5.7.1
	- installed components
		- /opt/dotfiles (from https://github.com/yagamy4680/dotfiles)
		- /root/.nodenv
		- /root/.vim
	- generated files
		- /opt/system
			OS_KERNEL       linux
			OS_DIST_NAME    ubuntu
			OS_DIST_CODENAME        trusty
			OS_ARCH x86_64
			OS_NAME linux-ubuntu-trusty


ubuntu-14.04.3-console-armhf-2016-02-11-raw-1700mb-v2.img.xz
	- date
		- 2016/07/07
	- base
		- bone-ubuntu-14.04.3-console-armhf-2016-02-11-2gb.img.xz
	- installed packages (extras)
		- parted
		- iotop
	- installed nodejs runtimes (via nodenv)
		- 4.4.7 (default)
		- 4.4.0
		- 6.3.0
	- installed components
		- /opt/dotfiles (from https://github.com/yagamy4680/dotfiles)
		- /root/.nodenv
		- /root/.vim
	- generated files
		- /opt/system
			OS_KERNEL       linux
			OS_DIST_NAME    ubuntu
			OS_DIST_CODENAME        trusty
			OS_ARCH x86_64
			OS_NAME linux-ubuntu-trusty

ubuntu-14.04.3-console-armhf-2016-02-11-raw-1700mb-v3.img.xz
	- date
		- 2016/07/24
	- base
		- bone-ubuntu-14.04.3-console-armhf-2016-02-11-2gb.img.xz
	- installed packages (extras)
		- N/A
	- installed nodejs runtimes (via nodenv)
		- 4.4.7 (default)
		- 4.4.0
		- 6.3.0
	- installed components
		- /opt/dotfiles (from https://github.com/yagamy4680/dotfiles)
		- /root/.nodenv
		- /root/.vim
	- extras
		- change default timezone to `Asia/Tokyo`
		- `update-rc.d apache2 disable`
		- `update-rc.d udhcpd disable`
		- `update-rc.d pppd-dns disable`


ubuntu-14.04.3-console-armhf-2016-02-11-raw-1700mb-v4.img.xz
	- date
		- 2016/11/08
	- base
		- bone-ubuntu-14.04.3-console-armhf-2016-02-11-2gb.img.xz
	- installed packages (extras)
		- N/A
	- installed nodejs runtimes (via nodenv)
		- 4.4.7 (default)
		- 4.4.0
		- 6.3.0
	- installed components
		- /opt/dotfiles (from https://github.com/yagamy4680/dotfiles)
		- /root/.nodenv
		- /root/.vim
	- extras
		- `apt-get remove apache2 -y && apt-get purge apache2 -y`
		- libudev-dev
		- libbluetooth-dev
		- bluetooth
		- bluez
