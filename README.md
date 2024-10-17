# arch-pkgbuilds
PKGBUILDs I have created for Arch/Artix Linux

I updated these packages because I wanted to be able to use rubyripper to rip my CD's. Please feel free to use these however you would like, and if someone who is a maintainer wishes to upload these on my behalf, that would be much appreciated (as I am otherwise unfamiliar with the process and it seems to involve some pre-existing community involvement in order to be able to do so)! On top of updating the source file location to be directly from rubygems.org, I have also updated the listed dependencies, which I got directly from that site (which I included alongside any necessary Arch packages). I am still learning how to create PKGBUILDs so if anyone has any advice or pointers, please do not hesitate to let me know!

In the event you are also trying to install rubyripper-git (the most recent rubyripper release binary has some issues w/ deprecated code), install the packages in this repo in the following order:

1. ruby-glib2
2. ruby-atk
3. ruby-cairo-gobject
4. ruby-gobject-introspection
5. ruby-gio2
6. ruby-gdk_pixbuf2
7. ruby-pango
8. ruby-gdk3
9. ruby-gtk3
10. rubyripper-git