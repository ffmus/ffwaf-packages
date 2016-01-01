include $(TOPDIR)/rules.mk

PKG_NAME:=gluon-switch2beta
PKG_VERSION:=1

PKG_BUILD_DIR := $(BUILD_DIR)/$(PKG_NAME)

include $(GLUONDIR)/include/package.mk

define Package/gluon-switch2beta
  SECTION:=gluon
  CATEGORY:=Gluon
  TITLE:=Switch autoupdater to beta branch if running in experimental branch 
  DEPENDS:=+gluon-core
endef

define Package/gluon-switch2beta/description
	Gluon community autoupdater firmware framework: Force update to beta, if in a experimental branch
endef

define Build/Prepare
	mkdir -p $(PKG_BUILD_DIR)
endef

define Build/Configure
endef

define Build/Compile
endef

define Package/gluon-switch2beta/install
	$(CP) ./files/* $(1)/
endef

define Package/gluon-switch2beta/postinst
endef

$(eval $(call BuildPackage,gluon-switch2beta))
