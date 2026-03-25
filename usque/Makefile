include $(TOPDIR)/rules.mk

PKG_NAME:=usque
PKG_VERSION:=1.4.2
PKG_RELEASE:=1

PKG_MAINTAINER:=Diniboy1123
PKG_LICENSE:=MIT

PKG_BUILD_DIR:=$(BUILD_DIR)/$(PKG_NAME)

include $(INCLUDE_DIR)/package.mk

define Package/usque
  SECTION:=net
  CATEGORY:=Network
  TITLE:=Diniboy1123 usque WARP client
  DEPENDS:=
endef

define Package/usque/description
  usque - Cloudflare WARP client by Diniboy1123
endef

define Build/Prepare
	true
endef

define Build/Configure
	true
endef

define Build/Compile
	true
endef

define Package/usque/install
	$(INSTALL_DIR) $(1)/usr/bin
	$(INSTALL_BIN) ./files/usque $(1)/usr/bin/usque
endef

$(eval $(call BuildPackage,usque))