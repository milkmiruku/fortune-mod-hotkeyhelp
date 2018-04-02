# Maintainer: Milk < milk on freenode >
pkgname=fortune-mod-hotkeyhelp
pkgver=1
pkgrel=3
pkgdesc="Hotkey reminder fortune cookie file"
arch=('any')
license=('custom:PublicDomain')
url="https://github.com/milkmiruku/fortune-mod-hotkeyhelp"
depends=('fortune-mod')
groups=('fortune-mods')

source=('hotkeyhelp')

build() {
	strfile ${srcdir}/hotkeyhelp ${srcdir}/hotkeyhelp.dat
}

package() {
	  install -D -m644 ${srcdir}/hotkeyhelp ${pkgdir}/usr/share/fortune/hotkeyhelp
	  install -D -m644 ${srcdir}/hotkeyhelp.dat ${pkgdir}/usr/share/fortune/hotkeyhelp.dat
}
