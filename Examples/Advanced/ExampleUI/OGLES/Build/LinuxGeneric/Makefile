#
# File			Makefile
# Title			Example makefile
#
# Copyright		Copyright (C) Imagination Technologies Limited.
#

.PHONY: clean

SDKDIR  = ../../../../../..
OUTNAME = OGLESExampleUI
DEPENDS =  PVRCore PVRAssets PVREgl PVRNativeGles PVRGles PVRShell PVRUIRenderer
LIBRARIES =  PVRUIRenderer PVRShell PVRGles PVRNativeGles PVREgl PVRAssets PVRCore
LIBPATHS =  ../../../../../../Framework/Bin/Linux_$(PLAT_SUFFIX)/$(DEBUG_RELEASE)$(WS)

OBJECTS +=	\
           OGLES/OGLESExampleUI.o

RESOURCES += \
           TexColShaderF_ES2.fsh\
           TexColShaderF_ES3.fsh\
           TexColShaderV_ES2.vsh\
           TexColShaderV_ES3.vsh\
           ColShaderF_ES2.fsh\
           ColShaderF_ES3.fsh\
           ColShaderV_ES2.vsh\
           ColShaderV_ES3.vsh\

COMMON_RESOURCES += \
           container-corner.pvr\
           container-filler.pvr\
           container-vertical.pvr\
           container-horizontal.pvr\
           topbar.pvr\
           background.pvr\
           clock-face.pvr\
           clock-face-small.pvr\
           hand.pvr\
           hand-small.pvr\
           battery.pvr\
           internet-web-browser.pvr\
           mail-message-new.pvr\
           network-wireless.pvr\
           office-calendar.pvr\
           weather-sun-cloud.pvr\
           weather-storm.pvr\
           weather-rain.pvr\
           text1.pvr\
           text2.pvr\
           text-weather.pvr\
           text-fri.pvr\
           text-sat.pvr\
           text-sun.pvr\
           text-mon.pvr\
           weather-sun-cloud-big.pvr\
           window-bottom.pvr\
           window-bottomcorner.pvr\
           window-side.pvr\
           window-top.pvr\
           window-topleft.pvr\
           window-topright.pvr\
           loremipsum.pvr\
           vertical-bar.pvr\


include $(SDKDIR)/Builds/Linux/make_example.mak
