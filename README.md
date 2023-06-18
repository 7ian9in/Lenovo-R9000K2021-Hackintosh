# Lenovo-R9000K2021-Hackintosh
# 详细参考
https://github.com/mocehu/Lenovo-Legion-R9000X2021R-Hackintosh <br>
https://github.com/zabdottler/Lenovo-Yoga-16S-hackintosh <br>

# 注意事项
1、本机型需要禁用一个xhci，详细操作参考上方链接，我禁用的是xhci 1 ，会造成蓝牙不可用。禁用xhci 0 会造成usb接口和键盘不能用，请谨慎操作！！！ <br>
2、我自己加装了一块 980 1T SSD，原装海力士固态需要禁用，详细操作参考上方链接！ <br>
3、其他bios设置大同小异，安装之前需要设置为混合模式，不然安装后加载核显驱动会自动重启！（bios版本GKEC60WW） <br>

# 目前问题（等大佬解决）
蓝牙不可用 <br>
内置扬声器和麦克风不可用（声卡是lac287，据说这个机型比较奇葩，直接打驱动不行...） <br>
摄像头不可用 <br>
触控板不可用 <br>
其他尚未详细测试... <br>
