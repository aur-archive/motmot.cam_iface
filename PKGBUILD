#Automatically generated by pip2arch on 2012-06-20

pkgname=motmot.cam_iface
pkgver=0.8.0
pkgrel=1
pkgdesc="cross-platform, cross-backend camera driver"
url="http://code.astraw.com/projects/motmot/cam_iface.html"
depends=('python2' )
makedepends=('python2-distribute' )
license=('BSD')
arch=('any')
source=('http://pypi.python.org/packages/source/m/motmot.cam_iface/motmot.cam_iface-0.8.0.zip')
md5sums=('714b1c60c4587f9744ef5059bb8dea51')

build() {
    cd $srcdir/motmot.cam_iface-0.8.0
    python2 setup.py build
}

package() {
    cd $srcdir/motmot.cam_iface-0.8.0
    python2 setup.py install --root="$pkgdir" --optimize=1 
}
