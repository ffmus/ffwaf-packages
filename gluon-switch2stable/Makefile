include $(TOPDIR)/rules.mk

PKG_NAME:=gluon-switch2stable
PKG_VERSION:=1

PKG_BUILD_DIR := $(BUILD_DIR)/$(PKG_NAME)

include $(GLUONDIR)/include/package.mk

define Package/gluon-switch2stable
  SECTION:=gluon
  CATEGORY:=Gluon
  TITLE:=Switch autoupdater to stable branch if running in beta branch 
  DEPENDS:=+gluon-core
endef

define Package/gluon-switch2stable/description
	Gluon community autoupdater firmware framework: Force update to stable, if in a beta branch
endef

define Build/Prepare
	mkdir -p $(PKG_BUILD_DIR)
endef

define Build/Configure
endef

define Build/Compile
endef

define Package/gluon-switch2stable/install
	$(CP) ./files/* $(1)/
endef

define Package/gluon-switch2stable/postinst
endef

$(eval $(call BuildPackage,gluon-switch2stable))
