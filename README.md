# exfat-nofuse

exFAT filesystem driver for the Linux kernel (from Samsung Electronics)

The [samsung](https://github.com/GalaxySubRepos/exfat-nofuse/tree/samsung) branch is merged from <https://github.com/bkuhn/exfat> and <https://github.com/jcadduono/linux_fs_exfat/tree/samsung>.  
The former provides versions from *1.1.0p1* to *1.2.4*. And the latter provides versions *1.2.23* and *1.2.24*.

The [linux_fs_exfa](https://github.com/GalaxySubRepos/exfat-nofuse/tree/linux_fs_exfat) branch is copied from <https://github.com/jcadduono/linux_fs_exfat/tree/master>.  
Although being [lonely](https://github.com/jcadduono/linux_fs_exfat/issues/1), it is still active at [Jul 15, 2017](https://github.com/jcadduono/linux_fs_exfat/commit/0b0b7bae8654f99b2d60a150a87bd00eca3b8a9a) to support kernel v4.12 .

The [exfat-nofuse)](https://github.com/GalaxySubRepos/exfat-nofuse/tree/exfat-nofuse) branch is copied from <https://github.com/dorimanx/exfat-nofuse>, which is the most famous one.  
See <https://github.com/dorimanx/exfat-nofuse/issues/5> and <https://lwn.net/Articles/560424/> for the license issue before Samsung [announcing](https://sfconservancy.org/news/2013/aug/16/exfat-samsung/) GPL. The whole story is reported by [WIRED](https://www.wired.com/2013/07/samsung-code/).

	kuhn/exfat
	Description: GPL'ed sources for the Samsung exfat module as released by Samsung.
	Website: https://gitorious.org/binbang/exfat-linux
	
	jcadduono/linux_fs_exfat
	exFAT filesystem driver for the Linux kernel (by Samsung Electronics Co., Ltd.)
	
	dorimanx/exfat-nofuse
	Android ARM Linux non-fuse read/write kernel driver for exFat and VFat Android file systems

## DKMS

DKMS support for [ArchLinux](https://aur.archlinux.org/packages/exfat-dkms-git/) and [Debian](https://github.com/azuwis/debian_exfat-nofuse/tree/master/debian) are available as `CONFIG_EXFAT_FS=m make` or so.

Unofficial Debian package scripts can be find at <https://github.com/azuwis/debian_exfat-nofuse/tree/master/debian>, and mirrored here.
