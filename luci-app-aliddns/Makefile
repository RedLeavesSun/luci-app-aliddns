#
# Copyright (C) 2018-2021 chenhw2 <https://github.com/chenhw2/>
#
# See /LICENSE for more information.
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI for ALiDDNS
LUCI_DEPENDS:=+openssl-util +curl
LUCI_PKGARCH:=all

PKG_NAME:=luci-app-aliddns
PKG_VERSION:=0.4.0
PKG_RELEASE:=1

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
