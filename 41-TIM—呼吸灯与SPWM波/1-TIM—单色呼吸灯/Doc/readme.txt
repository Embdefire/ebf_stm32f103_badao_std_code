/*********************************************************************************************/
【*】程序简介

-工程名称：单色呼吸灯
-实验平台: 野火STM32-F103 霸道 开发板 
-MDK版本：5.16
-ST固件库版本：3.5.0

【 ！】功能简介：
使用定时器输出控制LED灯呈呼吸效果


【*】注意事项：
若移植本程序到其它硬件上时，请注意要选用定时器通道引脚来控制LED灯

【 ！】实验操作：
编译并下载程序到开发板，复位后可以看到RGB灯呈呼吸效果

/*********************************************************************************************/


【*】 引脚分配

RGB灯：
	R_LED	<--->PB5(TIM3 CH2)
	G_LED	<--->PB0(TIM3 CH3)
	B_LED	<--->PB1(TIM3 CH4)
		
											

/*********************************************************************************************/

【*】 版本

-程序版本：1.0
-发布日期：2013-xx



/*********************************************************************************************/

【*】 联系我们

-野火论坛    :http://www.firebbs.cn
-淘宝店铺    :https://fire-stm32.taobao.com

/*********************************************************************************************/