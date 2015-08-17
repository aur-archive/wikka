# Maintainer: Sabart Otto - Seberm <seberm[at]gmail[dot]com>

pkgname=wikka
pkgver=1.3.3
pkgrel=2
pkgdesc="A flexible and lightweight wiki engine written in PHP, which uses MySQL to store pages."
arch=('any')
license=('custom')
depends=('php<5.3' 'mysql<5.5')
url="http://wikkawiki.org"
backup=()
install=wikka.install
source=(http://wikkawiki.org/downloads/Wikka-${pkgver}.tar.gz)

md5sums=('f2ab19fbf12bf98dad0b1ea4d8355b6e')

build() {
  #cd $srcdir/Wikka

  mkdir -p $pkgdir/srv/http/wikka/
  mv * $pkgdir/srv/http/wikka/
  touch $pkgdir/srv/http/wikka/wikka.config.php
  chmod 666 $pkgdir/srv/http/wikka/wikka.config.php
}
 
