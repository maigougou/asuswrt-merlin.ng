> **这是非官方改版，不是 Asuswrt-Merlin 或华硕的官方项目。** 这里的固件没有在真机上验证过，可能让路由器变砖，风险自负。
> 遇到问题请到[这里](https://github.com/maigougou/rt-ac86u-to-gt-ac2900/issues/new?template=hardware-report.md)反馈，不要找 Merlin 或华硕。
>
> Unofficial fork, not affiliated with Asuswrt-Merlin or ASUS. The firmware is untested on real hardware.

## RT-AC86U 160 MHz 改版

这个分支基于 Asuswrt-Merlin [386.14_2](https://github.com/RMerl/asuswrt-merlin.ng/tree/386.14_2)，让 RT-AC86U 保持原型号并启用 160 MHz。

- **下载固件：** [测试版 Release](https://github.com/maigougou/rt-ac86u-to-gt-ac2900/releases/tag/merlin-160-386.14_2-test1)。固件只发布在那里，这个仓库的 Releases 是空的。
- **教程和风险：** [编译和刷机教程](https://github.com/maigougou/rt-ac86u-to-gt-ac2900/blob/main/docs/build-merlin-160.md)
- **改了什么：** [查看改动](https://github.com/maigougou/asuswrt-merlin.ng/commit/26e18556)，只有 `target.mak` 和 RT-AC86U 的 `dhd.o` 两个文件。

以下是 Asuswrt-Merlin 原来的 README。

---

asuswrt-merlin New Gen (version 382.xx and higher)
==================================================

#### Support is available via the forums at [SNBForums](https://www.snbforums.com/forums/asuswrt-merlin.42/).

Asuswrt-Merlin is an enhanced version of Asuswrt, the firmware used by Asus's modern routers.

The goal of this project is to fix issues and bring some minor functionality adjustments to the 
original Asus firmware.  While some features do get added, this is not the main focus of this project.  
It is not meant to replace existing projects such as Tomato or DD-WRT, but rather to offer an alternative 
for people who prefer the original firmware featureset.

This is the new development branch, originally based on Asus's 
3.0.0.4.382_xxxx firmware release.  Development of the 380.xx 
legacy branch has been dropped.

Please consult the Wiki for an up-to-date list of supported models:

https://github.com/RMerl/asuswrt-merlin.ng/wiki/Supported-Devices
