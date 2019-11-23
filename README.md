# go-resvg
convert SVG to PNG or image using resvg library


# install
```shell
go get github.com/foolin/go-resvg
```

依赖：
https://github.com/ungerik/go-cairo
https://www.cairographics.org/

安装Cairo:
For Debian and Debian derivatives including Ubuntu:
```
sudo apt-get install libcairo2-dev
```
For Fedora:
```
sudo yum install cairo-devel
```

For openSUSE:
```
zypper install cairo-devel
```

Mac OS X
Using MacPorts, the port is called 'cairo', so you can just type:
```
   sudo port install cairo
```
And to upgrade to newer versions once installed:
```
   sudo port upgrade cairo
```
If you use fink instead, the command to install cairo is:
```
   sudo apt-get install cairo
```

Windows:
Precompiled binaries for Windows platforms can be obtained in a variety of ways.

From Dominic Lachowicz:

Since GTK+ 2.8 and newer depends on Cairo, you can have Cairo installed on Win32 as a side-effect of installing GTK+. For example, see The Glade/GTK+ for Windows Toolkit.

From Daniel Keep (edited by Kalle Vahlman):

Go to official GTK+ for Windows page.

https://www.gtk.org/download/
