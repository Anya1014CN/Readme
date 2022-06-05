How to flash custom rom

!!!You need PC or laptop than van connect to device and BACKUP YOUR DATA!!!

1.Install ADB and Fastboot on your PC(Search for guide on Google or Youtube)

2.Download LineageOS Recovery on your PC
[For Chopin](https://get.hancf.cn/Mi/chopin/chopin-los-rec.img)  or  [For choping](https://get.hancf.cn/Mi/choping/choping-los-rec.img)

2.Turn your phone into fastboot mode,start cmd or powershell,type "fastboot flash boot_ab <LineageOS Recovery filename>" to flash Lineage Recovery,then type "fastboot reboot recovery" to reboot into LineageOS Recovery. 

3.<Use volume key to move , power key to choose>
 First you should format userdata Factory reset > Format data/factory reset > Format data

4.When format is done, back to main menu, choose Apply update > Apply from ADB , then turn to your PC,type "adb sideload <Rom filename>" to sideload ROM package

5.When ADB starts sideloading ROMs, you can go and enjoy some afternoon tea :)

6.When ROM flash done,choose Reboot system now, and enjoy yourself :)


Late Updated:2022/06/05 5:40 UTC+8
