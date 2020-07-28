
export rtl8188eus(8812au) into drivers folder of your kernel source and add in kconfig 
source "drivers/aircrack_rtl8188eus_rtl8812au_fork_android/rtl8188eus/Kconfig" 

and in makefile 
obj-y += aircrack_rtl8188eus_rtl8812au_fork_android/rtl8188eus 

and same for 8812au *makefile and kconfig located in drivers folder
