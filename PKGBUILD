pkgname=cpptest
pkgver=0.1
pkgrel=1
pkgdesc="c++ Test"
arch=("any")
url="https://github.com/danlove99/cpptest"
license=('GPL')
source=("git://github.com/danlove99/cpptest")
sha1sums=('SKIP')

package() {
    cd "$pkgname"
    mkdir -p $pkgdir/usr/bin
    install -D -m755 ./test.o $pkgdir/usr/bin/$pkgname
}
