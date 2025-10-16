TARGET := iphone:clang:latest:7.0
INSTALL_TARGET_PROCESSES = SpringBoard MobileSafari com.apple.Preferences
include $(THEOS)/makefiles/common.mk

TWEAK_NAME = welcam-tool
welcam-tool_FILES = Tweak.xm
welcam-tool_FRAMEWORKS = UIKit WebKit
welcam-tool_CFLAGS = -fobjc-arc

include $(THEOS_MAKE_PATH)/tweak.mk