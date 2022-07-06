类原生系统刷入教程

!!!你需要一个可以连接你的手机的电脑/笔记本，强烈建议再开始之前备份你的数据!!!

1.在电脑上安装ADB和fastboot(自行搜索，这里不提供教程)

2.在电脑上下载LineageOS Recovery
[国行版-Chopin](https://get.hancf.cn/Mi/chopin/chopin-los-rec.img)  或者  [全球版-choping](https://get.hancf.cn/Mi/choping/choping-los-rec.img)

2.进入fastboot模式，然后 Windows徽标 + R ，输入cmd并回车，打开命令提示符，输入：

    fastboot flash boot_ab chopin-los-rec.img

或者

    fastboot flash boot_ab choping-los-rec.img

来刷入Lineage Recovery,刷入完成后，输入：

    fastboot set_active b

来切换到slot b,然后输入下面的命令来重启到recovery:

    fastboot reboot recovery

3.<用音量键移动光标 , 电源键选择>
 首先你应该恢复出厂设置： Factory reset > Format data/factory reset > Format data

4.恢复完成后, 返回到主菜单, 选择 Apply update > Apply from ADB , 然后在cmd窗口输入：

     adb sideload <Rom文件名>

来刷入类原生

5.刷入完成后，手动重启到fastboot，然后输入

    fastboot set_active a

来切换到slot a，然后输入：

    fastboot reboot

等待开机即可


Late Updated:2022/07/6 16:13 UTC+8
