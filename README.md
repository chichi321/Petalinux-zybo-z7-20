# Petalinux-zybo-z7-20
一个可在Xilinx z7-20 arm上运行的linux系统
## 注意事项
1. 需要将sd卡的第一个分区设置为FAT(网上有教程)
2. 将BOOT.bin和image.ub放入第一个分区
3. 打开串口调试程序(e.g. minicom),设置为115200/8/N/1，在linux下UART一般为/dev/ttyUSB1
4. 将z7-20连接到电脑，使用sd卡启动，会在屏幕上显示启动信息,账号密码均为root。
