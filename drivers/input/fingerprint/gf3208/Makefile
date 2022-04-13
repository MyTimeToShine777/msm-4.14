ccflags-y += -mllvm -inline-threshold=15000
ccflags-y += -mllvm -inlinehint-threshold=10000

obj-$(CONFIG_FINGERPRINT_GF3208) := gf_spi.o platform.o netlink.o

# Uncomment to enable goodix gestures (unneeded on FoD devices)
# subdir-ccflags-y += -DGOODIX_GESTURE_SWITCH
