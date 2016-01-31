This is mirror of [afsctool 1.6.4 (build 34)](http://brkirch.wordpress.com/afsctool/)

[Homepage](http://brkirch.wordpress.com/afsctool/)

AFSC (Apple File System Compression) tool is an utility that can be used to apply HFS+ compression to file(s), decompress HFS+ compressed file(s), or get information about existing HFS+ compressed file(s).  Mac OS 10.6 or later is required.

To build:

```sh
cc -o afsctool afsctool.c -framework CoreFoundation -framework CoreServices -lz
```

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/diimdeep/afsctool/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

