# Maintainer: Chris Down <chris@chrisdown.name>

pkgname=yturl
pkgver=1.15.3
pkgrel=1
pkgdesc="Print direct URLs to YouTube videos."
url=http://github.com/cdown/yturl
arch=( any )
license=( MIT )
depends=( python )
source=( "https://github.com/cdown/yturl/archive/v${pkgver}.zip" )
md5sums=('5b76704f2cd6d7dd51dd255f8282d1e5')

package() {
    install -D -m755 \
        "$srcdir/$pkgname-$pkgver/yturl" \
        "$pkgdir/usr/bin/yturl"
}
