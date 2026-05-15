#Owned by DairyMan@Whirlpool
# 
#Copyright GNU act.
include $(TOPDIR)/rules.mk

PKG_NAME:=ext-rooter-lite
PKG_VERSION:=1.000
PKG_RELEASE:=1

PKG_MAINTAINER:=Created by DM/makefile by Cobia@whirlpool
include $(INCLUDE_DIR)/package.mk

define Package/ext-rooter-lite
  SECTION:=utils
  CATEGORY:=ROOter
  DEPENDS:=+luci +ext-rooter-basic +pingtest +ext-logo \
		+ext-multimodem \
		+464xlat +webconsole \
		+ext-theme +ext-login \
		+ca-bundle +ca-certificates +libustream-wolfssl \
		+usb-storage \
		+luci-app-sqm +kmod-sched-cake +luci-app-nft-qos \
		+ext-command \
		+ext-extra +luci-app-hotspot +luci-app-wol +luci-app-guestwifi \
		+usbmuxd +libusbmuxd-utils +libimobiledevice-utils +kmod-usb-net-ipheth \
		+qlog +luci-ssl +usbutils +openssl-util +ethtool +ext-splashconfig \
		+nano +picocom +wpad-openssl +wget +qfirehose +luci-app-vpnbypass +ext-simplegps 
  TITLE:=ROOter support w/o MWan3 for 16meg and larger routers 
  PKGARCH:=all
endef

define Package/ext-rooter-lite/description
  Helper scripts to enable ROOter w/o MWan3 on 16meg and larger routers
endef


define Build/Compile
endef

$(eval $(call BuildPackage,ext-rooter-lite))
