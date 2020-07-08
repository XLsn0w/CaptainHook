TWEAK_NAME = WiFiViewer
NetworkList_FILES = Tweak.m
NetworkList_FRAMEWORKS = UIKit Security MessageUI
NetworkList_PRIVATE_FRAMEWORKS = Preferences

export TARGET=iphone:clang
export ARCHS = arm64

export TARGET_IPHONEOS_DEPLOYMENT_VERSION_arm64 = 11.0
export ADDITIONAL_OBJCFLAGS = -fobjc-arc -fvisibility=hidden
export INSTALL_TARGET_PROCESSES = Preferences

include $(THEOS)/makefiles/common.mk
include $(THEOS_MAKE_PATH)/tweak.mk
