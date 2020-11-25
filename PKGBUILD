# Maintainer: Dimitris Kiziridis <ragouel at outlook dot com>
# Modded by OakBricks

pkgname=eggs
pkgver=7.6.79
pkgrel=1
pkgdesc="A terminal utility, in active development, which allows you to remaster your system and redistribute it as an ISO image, on a USB stick or through the network via PXE remote boot"
arch=('x86_64')
url='https://penguins-eggs.net'
license=('GPL2')
depends=('python'
         'xdg-utils'
         'nodejs')
options=('!strip')
makedepends=('tar')
source=("${pkgname}-${pkgver}.deb::https://master.dl.sourceforge.net/project/penguins-eggs/packages-deb/eggs_${pkgver}-1_amd64.deb?viasf=1")
sha256sums=('SKIP')

package() {
  tar xvf data.tar.xz -C "${pkgdir}"
}
# vim:set ts=2 sw=2 et:
