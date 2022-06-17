How to flash custom rom

!!!You need PC or laptop than can connect to device and BACKUP YOUR DATA!!!

1.Install ADB and Fastboot on your PC(Search for guide on Google or Youtube)

2.Download LineageOS Recovery on your PC
[For Chopin](https://get.hancf.cn/Mi/chopin/chopin-los-rec.img)  or  [For choping](https://get.hancf.cn/Mi/choping/choping-los-rec.img)

2.Turn your phone into fastboot mode,start cmd or powershell,type:

    fastboot flash boot_ab chopin-los-rec.img

or

    fastboot flash boot_ab choping-los-rec.img

to flash Lineage Recovery,When flash finished,type:

    fastboot set_active b

To switch to slot b,then reboot to recovery:

    fastboot reboot recovery

3.<Use volume key to move , power key to choose>
 First you should format userdata Factory reset > Format data/factory reset > Format data

4.When format is done, back to main menu, choose Apply update > Apply from ADB , then turn to your PC,type:

     adb sideload <Rom filename>

to sideload ROM package

5.When ADB starts sideloading ROMs, you can go and enjoy some afternoon tea :)

6.When ROM flash done,reboot to fastboot,then type:

    fastboot set_active a

to switch to slot a,then Reboot system,type:

    fastboot reboot

 and enjoy yourself :)


Late Updated:2022/06/18 00:06 UTC+8
