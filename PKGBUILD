# Maintainer: Noa Himesaka <himesaka@noa.codes>
pkgname=t2strap
pkgver=0.1.0
pkgrel=1
pkgdesc="A pacstrap frontend to install Arch Linux on Macs with T2 security chip"
arch=('x86_64')
license=('GPL2')
depends=('arch-install-scripts' 'python')
makedepends=('git')
source=("src::git+https://github.com/NoaHimesaka1873/t2strap.git")
sha256sums=('SKIP')

build() {
 echo "No build needed"
}
package() {
    cd "$srcdir/src"
    install -Dm755 t2strap "$pkgdir/usr/bin/t2strap"
}
