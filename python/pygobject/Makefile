PKG_NAME = pygobject
PKG_VERS = 3.52.3
PKG_EXT = tar.gz
PKG_DIST_NAME = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = https://files.pythonhosted.org/packages/source/p/pygobject
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)

HOMEPAGE = https://pygobject.gnome.org/
COMMENT  = PyGObject is a Python package which provides bindings for GObject based libraries such as GTK, GStreamer, WebKitGTK, GLib, GIO and many more.
LICENSE  = LGPLv2.1+

DEPENDS = cross/gobject-introspection
DEPENDS += python/pycairo

include ../../mk/spksrc.python-wheel-meson.mk
