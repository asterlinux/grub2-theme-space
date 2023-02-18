# Maintainer: Sahan Rasanjana <sahan.user@gmail.com>
pkgname=grub2-theme-space
pkgver=2
pkgrel=2
pkgdesc="Minimalistic theme for grub"
arch=("x86_64")
url="https://github.com/asterlinux/grub2-theme-space"
license=('GPL')
depends=("grub")
install=space-grub.install
source=("space.tar.gz")
md5sums=("SKIP")

package() {
	mkdir -p "${pkgdir}/usr/share/grub/themes/"
	cp -r "${srcdir}/space/" "${pkgdir}/usr/share/grub/themes/"
}
