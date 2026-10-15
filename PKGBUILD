# Maintainer: James Oakey
pkgname=countdowns
pkgver=1.0
pkgrel=1
pkgdesc="Labelled countdowns to a date and time, shown on the conky desktop widgets"
arch=('any')
url="https://github.com/joakee/countdowns"
license=('unknown')   # no LICENSE file in the repo yet
depends=('python' 'python-gobject' 'gtk3')
# Built straight from this checkout, so there is nothing to checksum.
source=('countdowns'
        'countdowns.desktop')
sha256sums=('SKIP'
            'SKIP')

package() {
    install -Dm755 countdowns "$pkgdir/usr/bin/countdowns"
    install -Dm644 countdowns.desktop \
        "$pkgdir/usr/share/applications/countdowns.desktop"
}
