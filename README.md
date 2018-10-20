# libxslt-win-build

libxslt Windows build with Visual Studio.

This version is libxslt-1.1.32.

See win-build-info for general information about the
win-build effort.

To build, simply open the required solution file, and
you know how to use Visual Studio, right?
(or perhaps this is the wrong place for you.)

Depends on libxml2-win-build and hence libiconv-win-build and zlib-win-build.
There are hard references assuming all three libiconv-win-build, zlib-win-build,
and libxml2-win-build sit next to libxslt-win-build.

Basically, in a command prompt:

> \> cd {somewhere}\\  
> \> git clone https://github.com/kiyolee/libiconv-win-build.git  
> \> git clone https://github.com/kiyolee/zlib-win-build.git  
> \> git clone https://github.com/kiyolee/libxml2-win-build.git  
> \> git clone https://github.com/kiyolee/libxslt-win-build.git

Build libiconv and zlib first and then libxml2 and finally libxslt, with the same corresponding Visual Studio solution of course.
