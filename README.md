[![Build status](https://ci.appveyor.com/api/projects/status/bhqp9ib4bkv951w4?svg=true)](https://ci.appveyor.com/project/dimov-cz/win-sshfs)
|
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=winsshfs%40gmail%2ecom&lc=GB&item_name=WinSSHFS%20support%20donation&item_number=WinSSHFS&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted)
[![Donate](https://img.shields.io/badge/donate-bitcoin-green.svg)](https://foreveryone-cz.github.io/WinSshFS/donate-bitcoin/)
|
[![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/Foreveryone-cz/win-sshfs.svg)](http://isitmaintained.com/project/Foreveryone-cz/win-sshfs "Average time to resolve an issue")
[![Percentage of issues still open](http://isitmaintained.com/badge/open/Foreveryone-cz/win-sshfs.svg)](http://isitmaintained.com/project/Foreveryone-cz/win-sshfs "Percentage of issues still open")

Dokan-NetClient
========================

[本次更新]

*   支持最新版本的Dokan内核,建议Dokan内核版本>1.4.0.1000版本
*   修改SftpFilesystem类支持适配最新版本的Dokan内核
*   NetFramework版本升级到4.8最新版本

[接下来的计划]

*  保持与Dokan内核版本同步更新。
*  更新Renci.SshNet内核库版本,以便于更稳定
*  利用dotnet4.8新版本的语法梳理代码

[PR提交]

欢迎大家提交PR,我们一起完善这个东西,这个东西是因为我们项目中需要用到，所以才一直保持更新状态.

[注意事项]

感谢本项目的作者，如果您是本项目的作者，欢迎您提交PR，愿意把代码与您合并，然后一起完善这个项目,谢谢！


Main features:
*   Windows 10 Support
*   Puttyant (Pageant) support
*   Support for Android hosts (tested with CyanogenMod 11 [Android 4.4], requires busybox to be installed)
*   Spooldrive - remote hosts can by mounted as directories on same virtual drive
*   archive flag of file in windows represents and controls permission for group:
    *   ON => group have same rights as owner
    *   OFF => same rights as others)
*   Ability to use Proxy for connections
*   Send Keepalive packets. (Not configurable, each 60sec hardcoded)

![img](https://cloud.githubusercontent.com/assets/1085397/10747956/3f684d3a-7c18-11e5-8ca6-0f37a60426e4.jpg "UI")

Development version:
 [![Build status](https://ci.appveyor.com/api/projects/status/bhqp9ib4bkv951w4/branch/devel?svg=true)](https://ci.appveyor.com/project/dimov-cz/win-sshfs/branch/devel)
 
