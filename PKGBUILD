# Maintainer: Andrew Bezzubtsev <bezzubtsev.andrew@gmail.com>

pkgname=aut
pkgver="11_07_2017"
pkgrel=1
pkgdesc="ArchLinux Upgrade Tool"
arch=('x86_64' 'i686')
url="https://github.com/Andrew-Bezzubtsev/$pkgname"
license=('GPL')
groups=()
provides=()
depends=('zenity' 'gksu')
source=("$url/releases/download/$pkgver/$pkgname-$pkgver.tar.xz")

md5sums=()

package() {
	cd $srcdir/$pkgname-$pkgver/
	mkdir -p $pkgdir/usr/bin/
	install aut $pkgdir/usr/bin/
}
