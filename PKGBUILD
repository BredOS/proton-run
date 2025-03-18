# Maintainer: Bill Sideris <bill88t@bredos.org>

pkgname=proton-run
pkgver=1.0
pkgrel=1
pkgdesc="A utility to run windows executables using steam's proton."
url="https://bredos.org"
arch=(any)
license=(gpl3)
depends=(steam python)
source=("proton-run")
sha256sums=('SKIP')

package() {
    install -Dm755 "${srcdir}/proton-run" "${pkgdir}/usr/bin/proton-run"
}
