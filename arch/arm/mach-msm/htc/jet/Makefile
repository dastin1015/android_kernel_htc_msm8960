obj-$(CONFIG_MACH_JET) += board-jet.o
obj-$(CONFIG_MACH_JET) += board-jet-regulator.o
obj-$(CONFIG_MACH_JET) += board-jet-gpiomux.o
obj-$(CONFIG_MACH_JET) += board-jet-storage.o
obj-$(CONFIG_MACH_JET) += board-jet-audio.o
obj-$(CONFIG_MACH_JET) += board-jet-pmic.o
obj-$(CONFIG_MACH_JET) += board-jet-keypad.o
obj-$(CONFIG_MACH_JET) += board-jet-gpu.o
ifeq ($(CONFIG_MSM_CAMERA),y)
obj-$(CONFIG_MACH_JET) += board-jet-camera.o
endif
obj-$(CONFIG_MACH_JET) += display/
CFLAGS_board-jet-display.o += -Idrivers/video
