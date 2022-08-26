# theme

This is my plymouth script based theme.

You are required to move/copy the theme folder cloned from here via

git clone https://github.com/Bha-Gu/theme

to the directory

"/usr/share/plymouth/themes/theme/"

You may also remove the LICENCE and README files before installing.

You may make a link the vender logo at 

"/sys/firmware/acpi/bgrt/image"

to 

"/usr/share/plymouth/themes/theme/logo.png"

To install the theme run

sudo plymouth-set-default-theme -R theme

Assuming your distro is using/has installed the complete version of plymouth and not the "lite" version.

For distros with "lite" version of plymouth 

**TBA**

