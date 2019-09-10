# openwrt-dl and LEDE project

#### Description
#openwrt dl folder for China Internal user before building image

#improve your building time

1. sudo apt-get update

2. sudo apt-get -y install build-essential asciidoc binutils bzip2 gawk gettext git libncurses5-dev libz-dev patch unzip zlib1g-dev lib32gcc1 libc6-dev-i386 subversion flex uglifyjs git-core gcc-multilib p7zip p7zip-full msmtp libssl-dev texinfo libglib2.0-dev xmlto qemu-utils upx libelf-dev autoconf automake libtool autopoint

3. git clone https://github.com/coolsnowwolf/lede AND cd lede

4. ./scripts/feeds update -a 
   ./scripts/feeds install -a
   make menuconfig
 
5. make V=s

#### Software Architecture
Build image for self

#### Welcome to submit your packages
