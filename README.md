### New NodeMCU setup

Build a new firmare at http://nodemcu-build.com

``` bash
esptool --port COM3 erase_flash
esptool --port COM3 write_flash -fm dio 0x00000 thefirmware.bin
```
