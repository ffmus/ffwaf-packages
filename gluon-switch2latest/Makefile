include $(TOPDIR)/rules.mk

PKG_NAME:=gluon-switch2latest
PKG_VERSION:=1

PKG_BUILD_DIR := $(BUILD_DIR)/$(PKG_NAME)

include $(GLUONDIR)/include/package.mk

define Package/gluon-switch2latest
  SECTION:=gluon
  CATEGORY:=Gluon
  TITLE:=Switch autoupdater to latest branch
  DEPENDS:=+gluon-core
endef

define Package/gluon-switch2latest/description
	Gluon community autoupdater firmware framework: Force update to latest
endef

define Build/Prepare
	mkdir -p $(PKG_BUILD_DIR)
endef

define Build/Configure
endef

define Build/Compile
endef

define Package/gluon-switch2latest/install
	$(CP) ./files/* $(1)/
endef

define Package/gluon-switch2latest/postinst
endef

$(eval $(call BuildPackage,gluon-switch2latest))
