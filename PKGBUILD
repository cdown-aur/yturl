# Maintainer: Chris Down <chris@chrisdown.name>

pkgname="yturl"
pkgver=1.14.0
pkgrel=1
pkgdesc="Get direct media URLs to YouTube videos"
url="http://github.com/cdown/yturl"
arch=( "any" )
license=( "MIT" )
depends=( "python2" )
source=(
    "https://github.com/cdown/yturl/archive/v${pkgver}.zip"
)
md5sums=('76be42cc33a69a1a5a3d179b3dba1601')

package() {
    install -D -m755 \
        "$srcdir/$pkgname-$pkgver/yturl" \
        "$pkgdir/usr/bin/yturl"
}
