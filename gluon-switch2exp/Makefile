include $(TOPDIR)/rules.mk

PKG_NAME:=gluon-switch2exp
PKG_VERSION:=1

PKG_BUILD_DIR := $(BUILD_DIR)/$(PKG_NAME)

include $(GLUONDIR)/include/package.mk

define Package/gluon-switch2exp
  SECTION:=gluon
  CATEGORY:=Gluon
  TITLE:=Switch autoupdater to experimental
  DEPENDS:=+gluon-core
endef

define Package/gluon-switch2exp/description
	Gluon communitiiy autoupdater firmware framework: Force update to experimental
endef

define Build/Prepare
	mkdir -p $(PKG_BUILD_DIR)
endef

define Build/Configure
endef

define Build/Compile
endef

define Package/gluon-switch2exp/install
	$(CP) ./files/* $(1)/
endef

define Package/gluon-switch2exp/postinst
endef

$(eval $(call BuildPackage,gluon-switch2exp))
