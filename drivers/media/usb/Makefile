#
# Makefile for the USB media device drivers
#

# DVB USB-only drivers
obj-y += ttusb-dec/ ttusb-budget/ dvb-usb/ dvb-usb-v2/ siano/ b2c2/
obj-y += zr364xx/ stkwebcam/ s2255/

obj-$(CPTCFG_USB_VIDEO_CLASS)	+= uvc/
obj-$(CPTCFG_USB_GSPCA)         += gspca/
obj-$(CPTCFG_USB_PWC)           += pwc/
obj-$(CPTCFG_USB_AIRSPY)        += airspy/
obj-$(CPTCFG_USB_HACKRF)        += hackrf/
obj-$(CPTCFG_USB_MSI2500)       += msi2500/
obj-$(CPTCFG_VIDEO_CPIA2) += cpia2/
obj-$(CPTCFG_VIDEO_AU0828) += au0828/
obj-$(CPTCFG_VIDEO_HDPVR)	+= hdpvr/
obj-$(CPTCFG_VIDEO_PVRUSB2) += pvrusb2/
obj-$(CPTCFG_VIDEO_USBVISION) += usbvision/
obj-$(CPTCFG_VIDEO_STK1160) += stk1160/
obj-$(CPTCFG_VIDEO_CX231XX) += cx231xx/
obj-$(CPTCFG_VIDEO_TM6000) += tm6000/
obj-$(CPTCFG_VIDEO_EM28XX) += em28xx/
obj-$(CPTCFG_VIDEO_USBTV) += usbtv/
obj-$(CPTCFG_VIDEO_GO7007) += go7007/
obj-$(CPTCFG_DVB_AS102) += as102/
