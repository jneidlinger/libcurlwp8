libcurlwp8
==========

libcurl for Windows Phone 8

Curl 7.33.0

Build instructions

Open the Visual Studio solution at \curl-7.33.0\vs\vc12\vc12libcurl.sln

The build depends on zlib and OpenSSL. You need to configure the project includes to point to zlib and OpenSSL headers.

Notable changes:

A preprocessor definition, WINPHONE was added which does most of the WP8 specific work.

TODO:
I'll be adding an "example" Windows Runtime component that wraps some libcurl functionality, demonstrating using libcurl from an actual Windows Phone 8 app.