### Forked of  [timdoug unpkg](https://github.com/timdoug/unpkg)

- Download My Release ➣ [UN-PKG.zip](https://raw.githubusercontent.com/chris1111/unpkg/master/UN-PKG.zip)
Small Video
==================

https://user-images.githubusercontent.com/6248794/105172564-cee81f80-5aed-11eb-9b7c-3ac7c07a1f8d.mov

==================


![Modular Image Creation](https://i25.servimg.com/u/f25/18/50/18/69/captu662.png)
- The files will be extract in the same directory of the package 



Build instructions
==================

1.  Download and install Platypus (http://www.sveinbjorn.org/platypus).
2.  From Platypus->Preferences, install the command line tool.
3.  echo "4.5-beta" >VERSION
4.  make

To build xar and cpio
---------------------

1.  Download the most recent xar and libarchive source from opensource.apple.com.
2.  Use the instructions here: http://www.timdoug.com/log/2010/08/25/ to build fat binaries.
3.  For libarchive, make sure to add "--enable-bsdcpio --disable-bsdtar" to the config line.
