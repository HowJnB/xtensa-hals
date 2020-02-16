Hardware Abstraction Library for Xtensa ESP32-S2
================================================
2019-08-27

This is the libhal part of the SDK.


Requirements
------------
The following things are assumed to be true before you start:

- You have GNU autotools installed.
- You have a cross-compiler in `~/.../xtensa-esp32s2-elf/bin` in PATH.
- The programs in `~/.../xtensa-esp32s2-elf/bin` are all prefixed with `xtensa-esp32s2-elf-`,

Building
--------
To build, install a cross-compiler for Xtensa ESP32-S2, then run

    autoreconf -i
    PATH=~/.../xtensa-esp32s2-elf/bin:$PATH
    mkdir build
    cd build
    ../configure --host=xtensa-esp32s2-elf
    make


License
-------
Distributed under the MIT license. See the LICENSE file.
