---
layout: default
---
[xde-theme-telcom -- read me first file.  2014-09-12]: #

xde-theme-telcom
===============

Package `xde-theme-telcom-1.1.4` was released under CCPL:cc-by-nc-nd-3.0
license 2014-09-12.

This is a theme and a set of backgrounds for the _XDE (X Desktop
Environment)_ that provides a set of backgrounds on
a Telephone Switches and Offices theme.
This theme uses the Squared-cadet style from the [`xde-styles`][11]
package.

The source for `xde-theme-telcom` is hosted on [GitHub][1].


Release
-------

This is the `xde-theme-telcom-1.1.4` package, released 2014-09-12.
This release, and the latest version, can be obtained from [GitHub][1],
using a command such as:

    $> git clone https://github.com/bbidulock/xde-theme-telcom.git

Please see the [RELEASE][3] and [NEWS][4] files for release notes and
history of user visible changes for the current version, and the
[ChangeLog][5] file for a more detailed history of implementation
changes.  The [TODO][6] file lists features not yet implemented and
other outstanding items.

Please see the [INSTALL][8] file for installation instructions.

When working from `git(1)`, please use this file.  An abbreviated
installation procedure that works for most applications appears below.

This release is published under CCPL:cc-by-nc-nd-3.0 (primarily because
the base styles used to develop these styles were licensed under this
license).
Please see the license in the file [COPYING][10].


Quick Start
-----------

The quickest and easiest way to get `xde-theme-telcom` up and
running is to run the following commands:

    $> git clone https://github.com/bbidulock/xde-theme-telcom.git
    $> cd xde-theme-telcom
    $> ./autogen.sh
    $> ./configure
    $> make
    $> make DESTDIR="$pkgdir" install

This will configure, compile and install `xde-theme-telcom` the
quickest.  For those who like to spend the extra 15 seconds reading
`./configure --help`, some compile time options can be turned on and off
before the build.

For general information on GNU's `./configure`, see the file
[INSTALL][8].


Prerequisites
-------------

This package needs the [`xde-styles`][11] package to be useful and also
requires the `xde-setbg(1)` program from the [`xde-ctools`][12] package.


Issues
------

Report issues on GitHub [here][2].


Samples
-------

Following is a sample screenshot of the theme taken under the [ADWM][13]
window manager:

![adwm.jpg](scrot/adwm.jpg "Wallpaper #4")

Following are the six wallpapers included in the theme (consisting
primarily of pictures of really old telecommunications equipment in
Central Offices that I collected):

![cable_trays.jpg](images/cable_trays.jpg "Wallpaper #1")
![carrier_bays.jpg](images/carrier_bays.jpg "Wallpaper #2")
![channel_banks.jpg](images/channel_banks.jpg "Wallpaper #3")
![co_ailes.jpg](images/co_ailes.jpg "Wallpaper #4")
![switchboard.jpg](images/switchboard.jpg "Wallpaper #5")
![we1AESS9.jpg](images/we1AESS9.jpg "Wallpaper #6")



[1]: https://github.com/bbidulock/xde-theme-telcom
[2]: https://github.com/bbidulock/xde-theme-telcom/issues
[3]: https://github.com/bbidulock/xde-theme-telcom/blob/master/RELEASE
[4]: https://github.com/bbidulock/xde-theme-telcom/blob/master/NEWS
[5]: https://github.com/bbidulock/xde-theme-telcom/blob/master/ChangeLog
[6]: https://github.com/bbidulock/xde-theme-telcom/blob/master/TODO
[7]: https://github.com/bbidulock/xde-theme-telcom/blob/master/COMPLIANCE
[8]: https://github.com/bbidulock/xde-theme-telcom/blob/master/INSTALL
[9]: https://github.com/bbidulock/xde-theme-telcom/blob/master/LICENSE
[10]: https://github.com/bbidulock/xde-theme-telcom/blob/master/COPYING
[11]: https://github.com/bbidulock/xde-styles
[12]: https://github.com/bbidulock/xde-ctools
[13]: https://bbidulock.github.io/adwm

[ vim: set ft=markdown sw=4 tw=72 nocin nosi fo+=tcqlorn spell: ]: #
