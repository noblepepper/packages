include $(TOPDIR)/rules.mk

PKG_NAME:=gcc-arm-none-eabi
PKG_VERSION:=8-2019-q3-update-src.tar
PKG_RELEASE:=1

PKG_BUILD_DIR:=$(BUILD_DIR)/gcc-arm-none-eabi-$(PKG_VERSION)
PKG_SOURCE:=$(PKG_NAME)-$(PKG_VERSION).tar.bz2
PKG_SOURCE_URL:=https://developer.arm.com/-/media/Files/downloads/gnu-rm/8-2019q3/RC1.1/gcc-arm-none-eabi-8-2019-q3-update-src.tar.bz2?revision=94f1f227-7a58-49c6-910d-147d82b5a863?product=GNU%20Arm%20Embedded%20Toolchain,Invariant,,Source,8-2019-q3-update
PKG_HASH:=9b7dc52656f5cbec846a7ba3299f73bd

define Package/gcc-arm-none-eabi
  SECTION:=devel/
  CATEGORY:=embeded
  TITLE:=Toolchain for arm mcus

define Package/bridge/description
 Ethernet bridging configuration utility
  Manage ethernet bridging; a way to connect networks together to
   form a larger network.
   endef

define Build/Configure
  endef

define Package/bridge/install
		endef

$(eval $(call BuildPackage,bridge))
