# Maintainer: Chris Down <chris@chrisdown.name>

pkgname="yturl"
pkgver=1.10
pkgrel=1
pkgdesc="Get direct media URLs to YouTube videos"
url="http://github.com/cdown/yturl"
arch=( "any" )
license=( "MIT" )
depends=( "python2" )
source=(
    "https://github.com/cdown/yturl/archive/v${pkgver}.zip"
)
md5sums=('36c85d0ff5a34e31101784816f216f02')

package() {
    install -D -m755 \
        "$srcdir/$pkgname-$pkgver/yturl" \
        "$pkgdir/usr/bin/yturl"
}
