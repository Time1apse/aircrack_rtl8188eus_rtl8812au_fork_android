
export rtl8188eus(8812au) into drivers folder of your kernel source


add in kconfig 

source "drivers/aircrack_rtl8188eus_rtl8812au_fork_android/rtl8188eus/Kconfig" 

and in makefile 

obj-y += aircrack_rtl8188eus_rtl8812au_fork_android/rtl8188eus/


and same for 8812au 
*makefile and kconfig located in drivers folder

Use this https://forums.kali.org/showthread.php?37911-Getting-RTL8188-to-work-with-Kali-in-monitor-mode and add ";" on 1115 line in case of any errors
