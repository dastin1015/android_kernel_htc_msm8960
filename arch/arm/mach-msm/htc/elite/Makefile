obj-$(CONFIG_MACH_ELITE) += board-elite.o
obj-$(CONFIG_MACH_ELITE) += board-elite-regulator.o
obj-$(CONFIG_MACH_ELITE) += board-elite-gpiomux.o
obj-$(CONFIG_MACH_ELITE) += board-elite-storage.o
obj-$(CONFIG_MACH_ELITE) += board-elite-audio.o
obj-$(CONFIG_MACH_ELITE) += board-elite-pmic.o
obj-$(CONFIG_MACH_ELITE) += board-elite-keypad.o
obj-$(CONFIG_MACH_ELITE) += board-elite-gpu.o
ifeq ($(CONFIG_MSM_CAMERA),y)
obj-$(CONFIG_MACH_ELITE) += board-elite-camera.o
endif
obj-$(CONFIG_MACH_ELITE) += display/
CFLAGS_board-elite-display.o += -Idrivers/video
