#Maintainer: Nicolas Olmedo <ganjador@gmail.com>
#
pkgname=mirrorlist
pkgver=1
pkgdesc="Update mirrorlist for archlinux servers shit"
pkgrel=1
arch=(any)
license=('GPL')
depends=('pacman-contrib')
md5sums=('SKIP')

source=($pkgname)



package() {
	
	cd "${srcdir}"
	install -D -m755 $pkgname ${pkgdir}/usr/bin/${pkgname}

}
