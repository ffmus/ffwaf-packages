include $(TOPDIR)/rules.mk

PKG_NAME:=gluon-disableibss
PKG_VERSION:=1

PKG_BUILD_DIR := $(BUILD_DIR)/$(PKG_NAME)

include $(GLUONDIR)/include/package.mk

define Package/gluon-disableibss
  SECTION:=gluon
  CATEGORY:=Gluon
  TITLE:=Disable ibss/adhoc mesh if adhoc mesh is enabled and enable 802.11s instead: last step of migration to 802.11s
  DEPENDS:=+gluon-core
endef

define Package/gluon-disableibss/description
	Gluon community autoupdater firmware framework: Enable 802.11s mesh where requested
endef

define Build/Prepare
	mkdir -p $(PKG_BUILD_DIR)
endef

define Build/Configure
endef

define Build/Compile
endef

define Package/gluon-disableibss/install
	$(CP) ./files/* $(1)/
endef

define Package/gluon-disableibss/postinst
endef

$(eval $(call BuildPackage,gluon-disableibss))
