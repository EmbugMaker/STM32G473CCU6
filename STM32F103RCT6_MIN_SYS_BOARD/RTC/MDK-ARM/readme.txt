实验现象：
	PA9  TX
	PA10 RX
	usart1 @115200bps 8 n 1
	程序打印日期时间信息，复位后rtc不清零，仍然继续走。
	注意：需要修改rtc.c文件实现复位后计时不清除。
	使用MDK注意勾选 use microlib选项。