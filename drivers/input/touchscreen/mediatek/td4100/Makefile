# Linux driver folder
#include $(srctree)/drivers/misc/mediatek/Makefile.custom
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/td4100/

ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/$(MTK_PLATFORM)/include/

ccflags-y += -I$(srctree)/drivers/watchdog/mediatek/include/


obj-y +=  synaptics_dsx_rmi_dev.o
obj-y +=  synaptics_dsx_test_reporting.o
obj-y +=  synaptics_dsx_i2c.o
obj-y +=  synaptics_dsx_fw_update.o
# Gionee xuel 2016-3-17 Modify For Gesture Begin
obj-y +=  gn_tpd_feature.o
obj-y +=  synaptics_dsx_self_test.o
#obj-y +=  tpd_gesture.o
# Gionee xuel 2016-3-17 Modify For Gesture end
