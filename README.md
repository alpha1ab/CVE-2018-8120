# CVE-2018-8120
CVE-2018-8120 Windows LPE exploit

测试支持: Win7 x32, Win7 x64, Win2008 x32, Win2008 R2 x32, Win2008 R2 Datacenter x64, Win2008 Enterprise x64
         WinXP x32, Win2003 x32,Win2003 x64

原exp不支持xp，2003，当前代码在原基础上增加了对这两个系统的支持。

## Usage
```shell
CVE-2018-8120 exploit by @Topsec_Alpha_lab(https://github.com/alpha1ab)
Usage: exp.exe command
Example: exp.exe "net user admin admin /add"
```
## Caution
* 编译32位版本的exp,请从工程中排除shellcode.asm文件.

## Reference
* https://github.com/unamer/CVE-2018-8120
