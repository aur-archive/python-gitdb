# Maintainer: Jon Bergli Heier <snakebite@jvnv.net>

pkgname=python-gitdb
pkgver=0.5.4
pkgrel=1
pkgdesc="IO of git-style object databases"
arch=('i686' 'x86_64')
url="http://pypi.python.org/pypi/gitdb"
license=('BSD')
makedepends=('python2' 'python2-distribute')
depends=('python2' 'python-async>=0.6.1' 'python2-smmap>=0.8.0')
source=("http://pypi.python.org/packages/source/g/gitdb/gitdb-${pkgver}.tar.gz")

md5sums=('25353bb8d3ea527ba443dd88cd4e8a1c')

build() {
  cd "$srcdir/gitdb-$pkgver"
  python2 setup.py install --root="$pkgdir/" || return 1
}
# vim:set ts=2 sw=2 et:
