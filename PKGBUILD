# Maintainer: Safwan Nayeem Yousuf <safwannayeemyousuf.com>
pkgname=ramallahos-mpd-config
pkgver=1
pkgrel=1
pkgdesc="Kitty config for RamallahOS"
arch=('any')
url="https://github.com/ramallahos/$pkgname"
license=('GPL3')
depends=('mpd')
makedepends=('coreutils')
source=("$pkgname::git+$url.git")
sha256sums=('SKIP')

package() {
    cd "$pkgname"
    install -d "${pkgdir}/etc/skel/.config/mpd/"
    install -d "${pkgdir}/etc/skel/.config/mpd/playlists"
    install -Dm 644 "mpd.conf" "${pkgdir}/etc/skel/.config/mpd/mpd.conf"
}


