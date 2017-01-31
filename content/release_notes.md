# Release Notes

## 3.0.3

Published: January 01, 2017

* Disabled copy option for non-MPEG2 video streams
* Added parameter `-pix_fmt yuv420p` to transcoder
* Fixed displaying first video frame in frame button
* Changed transcoding caching to allow put multiple equal video files on DVD (e.g. with different cut points)
* Added support of EXIF metadata in slideshow
* Added CBR option for menu and slideshow enoding settings (disabled by default)
* Added Bulgarian translation (thanks to Ivan Dobrev)
* win32/win64: updated Manolito's VBR plug-in

## 3.0.2

Published: August 21, 2016

* Improved handling of process messages
* Changed encoding of menu and slideshow to use constant bitrate (CBR)
* Fixed using of transcoding cache after restarting of DVDStyler
* win32/win64: updated Manolito's VBR plug-in and enabled by default
* win32/win64: updated ffmpeg to version 3.1.2 (rogerdpack build with Windows-XP patch)
