# Lenovo-R9000K2021-Hackintosh
# 详细参考
https://github.com/mocehu/Lenovo-Legion-R9000X2021R-Hackintosh <br>
https://github.com/zabdottler/Lenovo-Yoga-16S-hackintosh <br>
https://github.com/NootInc/NootedRed <br>
**感谢以上各位大佬！！！**

# 机型信息
系统 macOS Ventura 13.5.1 <br>
MacBook Pro (13-inch, 2020, Two Thunderbolt 3 ports)<br>
处理器 3.2 GHz AMD Ryzen 7 5800H<br>
内存 32 GB 3200 MHz DDR4<br>
图形卡 AMD Radeon Graphics 4 GB<br>

# 注意事项(0821更新)
1、~~本机型需要禁用一个XCHI，详细操作参考上方链接，我禁用的是xhci 1 ，会造成**蓝牙**不可用。禁用xhci 0 会造成usb接口和键盘不能用，请谨慎操作！！！~~
**现在改为用 SSDT-XHC1-DISABLE.aml 来禁用xhci1。 不再需要操作bios**
<br>
2、我自己加装了一块 980 1T SSD，原装海力士固态需要禁用，详细操作参考上方链接！使用SSDT-NVME-DISABLE.aml 来禁用 <br>
3、其他bios设置大同小异，显存改为4G等等...安装之前需要设置为混合模式，不然安装后加载核显驱动会自动重启！（bios版本GKEC60WW） <br>
4、更新了一些驱动，删减了一些驱动（蓝牙等）<br>
5、修复触控板 <br>
6、更新至Ventura 13.5.1 <br>
7、三码需自行生成，NootedRed已禁用，安装完后请再启用。固态屏蔽文件SSDT-NVME-DISABLE.aml已禁用（按你的情况决定是否启用）

# 目前问题（等大佬解决）
偶尔卡顿  <br>
蓝牙、摄像头不可用 <br>
内置扬声器和麦克风不可用（声卡是alc287，据说这个机型比较奇葩，直接打驱动不行...） <br>
其他尚未详细测试... <br>
