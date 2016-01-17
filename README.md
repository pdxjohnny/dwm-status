#dwm-status

##Summary

Displays time, sysload, memory
consumption, battery level and network transfer speeds.

##Dependencies

For dwm the [statuscolor patch](http://dwm.suckless.org/patches/statuscolors)
is recommended.

##Usage

To install, run

	`go get github.com/pdxjohnny/dwm-status`

Then add the following line to your `.xinitrc` or whereever you start dwm, but
before actually starting dwm:

	`$GOPATH/bin/dwm-status &`

##Configuration

The dwm status bar can be easily modified, just by patching the source. You can
add new informational panels, remove others, change the ordering or formating.
With a custom font you can use own icons and separators and through the
statuscolors patch config in dwm you can change the colors.

##License

"THE BEER-WARE LICENSE" (Revision 42):
<teichm@in.tum.de> wrote this file. As long as you retain this notice you
can do whatever you want with this stuff. If we meet some day, and you think
this stuff is worth it, you can buy me a beer in return Markus Teich
