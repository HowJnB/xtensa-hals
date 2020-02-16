Hardware Abstraction Library for Xtensa ESP32
=============================================
2019-08-27

This is the libhal part of the SDK.


Requirements
------------
The following things are assumed to be true before you start:

- You have GNU autotools installed.
- You have a cross-compiler in `~/.../xtensa-esp32-elf/bin` in PATH.
- The programs in `~/.../xtensa-esp32-elf/bin` are all prefixed with `xtensa-esp32-elf-`,

Building
--------
To build, install a cross-compiler for Xtensa ESP32, then run

    autoreconf -i
    PATH=~/.../xtensa-esp32-elf/bin:$PATH
    mkdir build
    cd build
    ../configure --host=xtensa-esp32-elf
    make


License
-------
Distributed under the MIT license. See the LICENSE file.
