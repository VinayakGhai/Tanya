# Maintainer: Vinayak Ghai <VinayakGhai@users.noreply.github.com>
pkgname=tanya-bin
_pkgname=Tanya
pkgver=1.0.0
pkgrel=1
pkgdesc="Polyglot news aggregator scraping news using Rust, C++, Go, Java, Python"
arch=('x86_64')
url="https://github.com/VinayakGhai/Tanya"
license=('GPL2')
depends=('gtk3' 'nss' 'alsa-lib' 'libxss' 'glibc')
makedepends=('npm' 'git')
provides=('Tanya')
conflicts=('Tanya')
source=("${url}/releases/download/v${pkgver}/Tanya-${pkgver}-x86_64.AppImage")
sha256sums=('SKIP')

package() {
    install -Dm755 "${srcdir}/Tanya-${pkgver}-x86_64.AppImage" "${pkgdir}/usr/bin/${_pkgname}"
}
