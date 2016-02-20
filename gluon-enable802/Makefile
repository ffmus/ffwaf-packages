include $(TOPDIR)/rules.mk

PKG_NAME:=gluon-enable802
PKG_VERSION:=1

PKG_BUILD_DIR := $(BUILD_DIR)/$(PKG_NAME)

include $(GLUONDIR)/include/package.mk

define Package/gluon-enable802
  SECTION:=gluon
  CATEGORY:=Gluon
  TITLE:=Enable 802.11s mesh if adhoc mesh is enabled: First Step of migration to 802.11s
  DEPENDS:=+gluon-core
endef

define Package/gluon-enable802/description
	Gluon community autoupdater firmware framework: Enable 802.11s mesh where requested
endef

define Build/Prepare
	mkdir -p $(PKG_BUILD_DIR)
endef

define Build/Configure
endef

define Build/Compile
endef

define Package/gluon-enable802/install
	$(CP) ./files/* $(1)/
endef

define Package/gluon-enable802/postinst
endef

$(eval $(call BuildPackage,gluon-enable802))
