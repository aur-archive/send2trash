# Maintainer Kovivchak Evgen <oneonfire@gmail.com>

pkgname=send2trash
pkgver=1.3.0
pkgrel=1
pkgdesc="Send file to trash natively under Mac OS X, Windows and Linux."
arch=('any')
url="http://pypi.python.org/pypi/Send2Trash"
license=('BSD')
depends=('python2')
source=("Send2Trash-${pkgver}.tar.gz::http://pypi.python.org/packages/source/S/Send2Trash/Send2Trash-${pkgver}.tar.gz")
md5sums=('0fe9e60f2da76173d64ab1cdf0fd551b')

package() {
	cd ${srcdir}/Send2Trash-${pkgver}
	python2 setup.py install --root=$startdir/pkg
}

