TARGET := iphone:clang:latest:14.0
ARCHS = arm64 arm64e
INSTALL_TARGET_PROCESSES = SpringBoard

include $(THEOS)/makefiles/common.mk

TWEAK_NAME = Force5GHzTether

Force5GHzTether_FILES = Tweak.x
Force5GHzTether_CFLAGS = -fobjc-arc
Force5GHzTether_PRIVATE_FRAMEWORKS = MobileWiFi

include $(THEOS_MAKE_PATH)/tweak.mk