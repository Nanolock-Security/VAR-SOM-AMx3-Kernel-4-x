#
# TI Keystone SOC drivers
#
obj-$(CONFIG_KEYSTONE_DSP_MEM)		+= keystone_dsp_mem.o
obj-$(CONFIG_KEYSTONE_NAVIGATOR_QMSS)	+= knav_qmss.o
obj-$(CONFIG_KEYSTONE_NAVIGATOR_QMSS_QOS)	+= knav_qmss_qos.o
knav_qmss-y := knav_qmss_queue.o knav_qmss_acc.o $(knav_qmss_qos-y)
obj-$(CONFIG_KEYSTONE_NAVIGATOR_DMA)	+= knav_dma.o
obj-$(CONFIG_AMX3_PM)			+= pm33xx.o
obj-$(CONFIG_OPP_DOMAIN_TI)		+= ti-opp-domain.o
obj-$(CONFIG_WKUP_M3_IPC)		+= wkup_m3_ipc.o
obj-$(CONFIG_TI_SCI_PM_DOMAINS)		+= ti_sci_pm_domains.o
