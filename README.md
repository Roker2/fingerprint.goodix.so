By Roker2

## fingerprint.goodix.so

Okay, idea is increase memory allocation for Parcel. Since Android 10 Parcel need more memory.
It is not full list of patch places.
getFrameworkFingerID(int *, int) is completed.

ASM to HEX
http://shell-storm.org/online/Online-Assembler-and-Disassembler/?inst=STP+++++++++++++X29%2C+X30%2C+%5BSP%2C-0x160%5D%21&arch=arm64&as_format=inline#assembly

Original idea by @aranhid
https://github.com/aranhid/proprietary_vendor_xiaomi/commit/b33dfabcb392e635c532fbd547921a2d2c600833

| Function                           | Patch place | New memory size | Patch status (patched or not) |
| :--------------------------------- | :---------- | :-------------- | :---------------------------- |
| getFrameworkFingerID(int *, int)   | DD58        | -0x180          | No                            |
| getFrameworkFingerID(int *, int)   | DD94        | 0x180-8         | No                            |
| getFrameworkFingerID(int *, int)   | DDC8        | 0x100           | No                            |
| getFrameworkFingerID(int *, int)   | DF70        | 0x180-8         | No                            |
| getFrameworkFingerID(int *, int)   | DF94        | 0x180           | No                            |
| getFrameworkFingerID(int *, int)   | DFB4        | 0x100           | No                            |
| getFrameworkFingerID(int *, int)   | DFD0        | 0x100           | No                            |

## Comments ##
DF94 - LDP X29, X30, [SP],#0x160 (thanks IDA -_-)
#0x160+var_70 = #0xF0
#0x180+var_80 = #0x100