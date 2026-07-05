include $(TOPDIR)/rules.mk

PKG_NAME:=phoenix-core
PKG_VERSION:=0.1
PKG_RELEASE:=1

include $(INCLUDE_DIR)/package.mk

define Package/phoenix-core
  SECTION:=base
  CATEGORY:=Phoenix
  TITLE:=Phoenix Server Core
endef

define Package/phoenix-core/install
    $(INSTALL_DIR) $(1)/etc
    $(INSTALL_DATA) ./files/etc/phoenix-release $(1)/etc/
endef

$(eval $(call BuildPackage,phoenix-core))
