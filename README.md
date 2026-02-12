```
                       __
                      / _|
  _ ____      ___ __ | |_ ___
 | '_ \ \ /\ / / '_ \|  _/ __|
 | |_) \ V  V /| | | | | \__ \
 | .__/ \_/\_/ |_| |_|_| |___/
 | |
 |_|

Usage: pwnfs [OPTION] [FILE] 
pwnfs - tiny tool which can be used in the kernel-based CTF tasks in order to decompress or compress rootfs with exploit

List of mandatory options:
    -d decompress rootfs archive into the new directory
    -c compile the exploit, place it in the rootfs dir and compress rootfs
    -h print this help message

Example of usage:
    pwnfs -d rootfs.cpio - will decompress rootfs into the rootfs directory
    pwnfs -c exploit.c - will compile exploit, place ELF file in rootfs dir and then compress it to rootfs.cpio

```
