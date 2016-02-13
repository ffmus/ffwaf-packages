include $(TOPDIR)/rules.mk

PKG_NAME:=gluon-cleanupmesh
PKG_VERSION:=1

PKG_BUILD_DIR := $(BUILD_DIR)/$(PKG_NAME)

include $(GLUONDIR)/include/package.mk

define Package/gluon-cleanupmesh
  SECTION:=gluon
  CATEGORY:=Gluon
  TITLE:=Cleanup Mesh Radios with VLAN. Migration Error from ibss.
  DEPENDS:=+gluon-core
endef

define Package/gluon-switch2latest/description
	Gluon community autoupdater firmware framework: Cleanup migration error from ibss with vlans.
endef

define Build/Prepare
	mkdir -p $(PKG_BUILD_DIR)
endef

define Build/Configure
endef

define Build/Compile
endef

define Package/gluon-ceanupmesh/install
	$(CP) ./files/* $(1)/
endef

define Package/gluon-cleanupmesh/postinst
endef

$(eval $(call BuildPackage,gluon-cleanupmesh))
