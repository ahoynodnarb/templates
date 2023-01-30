export TARGET := iphone:clang:14.4
@@KILL_RULE@@

include @@THEOS@@/makefiles/common.mk

TWEAK_NAME = @@PROJECTNAME@@

$(TWEAK_NAME)_FILES = Tweak.x
$(TWEAK_NAME)_CFLAGS = -fobjc-arc

include $(THEOS_MAKE_PATH)/tweak.mk
