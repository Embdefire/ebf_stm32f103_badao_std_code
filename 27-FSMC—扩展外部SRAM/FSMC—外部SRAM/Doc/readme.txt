/*********************************************************************************************/
【*】程序简介

-工程名称：FSMC-SRAM
-实验平台: 野火STM32 霸道 开发板 
-MDK版本：5.16
-ST固件库版本：3.5

【 ！】功能简介：
读写板载的 SRAM 芯片。

学习目的：学习STM32的FSMC驱动及SRAM内存器。

【*】注意事项：
无

【 ！】实验操作：
电脑端使用串口调试助手，选择电脑与STM32相连的COM口，设置为115200-N-8-1，
复位开发板，即可接收STM32串口发送给电脑的调试信息。


【*】 引脚分配

SRAM （IS62WV51216 1MB 字节）：
SRAM芯片的接口与STM32的FSMC相连。
		/*控制信号线*/
		CS	<--->PG10 	(FSMC_NE3)
		WE	<--->PD5	(FSMC_NWE)
		OE	<--->PD4	(FSMC_NOE)
		UB	<--->PE1	(FSMC_NBL0)
		LB	<--->PE0	(FSMC_NBL1)
		
地址和数据信号线省略，本连接的SRAM基地址为 (0x68000000)，结束地址为(0x68100000),大小为1M字节


串口(TTL-USB TO USART)：
CH340的收发引脚与STM32的发收引脚相连。
	RX<--->PA9
	TX<--->PA10
												

/*********************************************************************************************/

【*】 版本

-程序版本：1.0
-发布日期：2013-10

/*********************************************************************************************/

【*】 联系我们

-野火论坛    :http://www.firebbs.cn
-淘宝店铺    :https://fire-stm32.taobao.com

/*********************************************************************************************/