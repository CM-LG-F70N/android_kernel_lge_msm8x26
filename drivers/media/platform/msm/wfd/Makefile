ifeq ($(CONFIG_MSM_WFD),y)
  obj-y += wfd-ioctl.o
  obj-y += wfd-util.o
  obj-y += vsg-subdev.o

  #pick up the MDP subdevice
  ifeq ($(CONFIG_FB_MSM_WRITEBACK_MSM_PANEL),y)
    obj-y += mdp-4-subdev.o

  endif

  #pick up the Encoder subdevice
  ifeq ($(CONFIG_MSM_VIDC_1080P),y)
    obj-y += enc-mfc-subdev.o
  endif

endif
