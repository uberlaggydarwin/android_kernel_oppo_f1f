#gt915 touchpanel driver


obj-$(CONFIG_GT9XX_TOUCHPANEL_DRIVER)	+= gt9xx.o
#ifdef VENDOR_EDIT /* LiuPing@Phone.BSP.Sensor, 2015/04/23, add for gt9xx gesture. */
obj-$(CONFIG_GT9XX_TOUCHPANEL_DRIVER)	+= circle_point.o
#endif /*VENDOR_EDIT*/
#gt915 update file
obj-$(CONFIG_GT9XX_TOUCHPANEL_UPDATE)	+= gt9xx_update.o
#debug tool
obj-$(CONFIG_GT9XX_TOUCHPANEL_DEBUG)	+= goodix_tool.o
