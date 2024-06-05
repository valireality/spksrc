PKG_VERS = 8.0.301
PKG_EXT = tar.gz
PKG_DIST_NAME = dotnet-sdk-$(PKG_VERS)-linux-x64.$(PKG_EXT)
PKG_DIST_SITE = https://download.visualstudio.microsoft.com/download/pr/86497c4f-3dc8-4ee7-9f6a-9e0464059427/293d074c28bbfd9410f4db8e021fa290


HOMEPAGE = https://dotnet.microsoft.com/
COMMENT  = A developer platform for building apps.
LICENSE  = MIT

INSTALL_TARGET = dotnet-install

DOTNET_PACKAGES=$(DISTRIB_DIR)/nuget/packages

include ../../mk/spksrc.native-install.mk

.PHONY: dotnet-install
dotnet-install:
	mkdir -p $(DOTNET_PACKAGES)
