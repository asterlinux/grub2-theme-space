# Maintainer: Sahan Rasanjana <sahan.user@gmail.com>
pkgname=grub2-theme-space
pkgver=1
pkgrel=8
pkgdesc="Minimalistic theme for grub"
arch=("x86_64")
url="https://github.com/asterlinux/grub2-theme-space"
license=('GPL')
depends=("grub")
install=space-grub.install
source=("space.tar.gz")
md5sums=("SKIP")

package() {
	mkdir -p "${pkgdir}/boot/grub/themes/"
	cp -r "${srcdir}/space/" "${pkgdir}/boot/grub/themes/"
}
