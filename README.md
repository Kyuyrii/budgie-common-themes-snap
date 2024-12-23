budgie-common-themes is a Snap that allows you to use several themes in Snap applications.

The GTK themes available in it were chosen based on Ubuntu Budgie, Fedora Budgie, Ultramarine and Arch.

I recommend using Papirus icons, mainly because it has a snap version that automatically connects with the applications:
https://github.com/PapirusDevelopmentTeam/papirus-icon-theme

budgie-common-themes needs gtk-common-themes to be removed, so as not to generate conflicts, so it will use gtk-theme-pop as a base to connect with the applications.

In the zip file that has the Snap files and the sh file for installation, I left a sh file to be used when you want to connect budgie-common-themes with the Snap applications currently installed.
