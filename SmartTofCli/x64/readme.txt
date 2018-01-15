1.命令行进入当前目录，输入下面命令进入交互模式。
dmcam-cli-rel.exe -i
2.使用下面命令升级(xxx为版本号，如flash mcu fw_mcu.bin 1 ，版本号1；xxx要比info命令返回的版本高才能升级)：
flash mcu fw_mcu.bin  xxx 
3.等待升级结束，红灯会闪烁一下。