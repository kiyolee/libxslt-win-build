# libxslt-win-build

libxslt Windows build with Visual Studio.

This version is libxslt-1.1.40.

Note that LZMA support is now available for libxml2-2.12.0 or later but only for VS2013 or later.

To build, simply open the required solution file, and
you know how to use Visual Studio, right?
(or perhaps this is the wrong place for you.)

Depends on:
* libxml2-win-build
* libiconv-win-build
* zlib-win-build
* xz-win-build (VS2013 or later)

There are hard references assuming all these sit next to libxslt-win-build.

Basically, in a command prompt:

> \> cd {somewhere}\\  
> \> git clone https://github.com/kiyolee/libiconv-win-build.git  
> \> git clone https://github.com/kiyolee/zlib-win-build.git  
> \> git clone https://github.com/kiyolee/xz-win-build.git (VS2013 or later)  
> \> git clone https://github.com/kiyolee/libxml2-win-build.git  
> \> git clone https://github.com/kiyolee/libxslt-win-build.git

Build all these dependencies in the suggested order as shown above and
finally libxslt, with the same corresponding Visual Studio solution of course.

This repository tracks only officially released versions of libxslt.
Check branch win-build of https://github.com/kiyolee/libxslt.git that follows latest development.
