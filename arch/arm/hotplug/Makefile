#EXTRA_CFLAGS += -w

cflags-y	+= -os

### HotPlugs ###
#obj-y	:= intelli_plug.o bricked_hotplug.o msm_zen_decision.o alucard_hotplug.o msm_hotplug.o mako_hotplug.o

obj-$(CONFIG_MSM_HOTPLUG) += msm_hotplug.o
obj-$(CONFIG_INTELLI_HOTPLUG) += intelli_plug.o
obj-$(CONFIG_BRICKED_HOTPLUG) += bricked_hotplug.o
obj-y += msm_zen_decision.o
obj-$(CONFIG_ALUCARD_HOTPLUG) += alucard_hotplug.o
obj-y += mako_hotplug.o
obj-y += thunderplug.o
obj-y += msm-sleeper.o
obj-y         += autosmp.o
obj-y += blu_plug.o
obj-y += fast_hotplug.o
#obj-y += aero_hotplug.o
obj-y += lazyplug.o
