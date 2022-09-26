# e-gtk-pro

A gtk-theme to match Enlightenment 0.25.x dark flat-look theme.

While there is already an older e-gtk theme, it doesn't work properly anymore -- as to be seen from the screenshots above.

There also is another issue with Enlightenment...

There is a system-file-manager icon missing on the fresh install, and if it is not missing, then it is the icon-set default one, which doesn't match the icon seen in Enlightenment File Manager (default yellow folder), and there is no Enlightenment icon-set at all. The old Enlightenment-X isn't flat-look, and is basically a Faenza with some recolored symbolics and a blue set of folders. Papirus theme that might come with the installation is flat, but it doesn't really fit well in the Enlightenment appearance -- it has folders in totally different blue color, and why blue folders at all, if the default Enlightenment File Manager is using yellow folders? Basically, Enlightenment File Manager will show you yellow folders, but any other file manager that you might be occasionally using (Caja, Nautilus, Nemo, SpaceFM, Thunar... to name only a few) will show you blue folders...

Disclaimer:
This theme is NOT intended to be used in any other cases, but solely in conjunction with Enlightenment 0.25.x.
It isn't a perfect theme though, but only the "quick'n'dirty" "Hotfix" for my personal use.
I'm sharing it here, because it might come handy for somebody.

Issues:
GTK 3.20 applications:
- mini-/maximize/close buttons will become invisible on hover (dark gray on dark gray prelight)
- Nautilus left (bookmarks) panel will have dark gray instead of blue highlighting
- light shadows instead of dark on some applications
- some other minor issues

It probably won't be fixed ever, because it would mean chasing one single color value in thousands of code lines ...

Tested on Fedora i3 with repository version Enlightenment 0.25.1 and on Ubuntu 22.04 LTS, with Enlightenment 0.25.4.

## Original Source: 
* [e-gtk-pro Enlightenment 0.25 GTK-theme and icon-set](https://www.pling.com/p/1909560/)
* [Bodhi green Enlightenment 0.25 GTK-theme and icon-set](https://www.pling.com/p/1909962/)
