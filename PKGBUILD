# Maintainer: Bruno Goncalves <bigbruno@gmail.com>

pkgname=dbus-broker-enable
pkgver=1.0.0
pkgrel=0
arch=('any')
license=('GPL')
url="https://github.com/biglinux/dbus-broker-enable"
pkgdesc="Automatic enable dbus-broker"
source=("git+https://github.com/biglinux/dbus-broker-enable.git")
depends=('dbus-broker')
md5sums=(SKIP)

package() {
    cp -r "${srcdir}/dbus-broker-enable/dbus-broker-enable/usr/" "${pkgdir}/"
} 
