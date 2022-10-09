pkgname=v2raya-openrc
pkgver=0.0.1
pkgrel=1
pkgdesc="OpenRC v2raya init script"
arch=('any')
url=""
depends=('openrc' 'v2raya')
license=('GPL')
source=('v2raya.init')
md5sums=('0e3956b8657a1e3493edd81ceae56380')

package () {
    cd "$srcdir"
    mkdir -p "$pkgdir/etc/init.d/"
    install -m755 "$srcdir/v2raya.init" "$pkgdir/etc/init.d/v2raya"
}
