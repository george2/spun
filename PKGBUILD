# Maintainer: george <rpubaddr0 {at} gmail [dot] com>

pkgname=spun
pkgver=0.1
pkgrel=1
pkgdesc='A simple pacman update notifier, using notify-send.'
arch=('any')
url='http://github.com/george2/spun/'
license=('none')
depends=('libnotify' 'bash')
install=$pkgname.install
source=('spun' 'spun.rc')
md5sums=('569cfb1239ddb18bcca4a4f0057aae43'
         'd4d3cb0ff57f7e17afed111703afe277')

package() {
  install -Dm755 spun "${pkgdir}/usr/bin/spun"
  install -Dm755 spun.rc "${pkgdir}/etc/rc.d/spun"
}
