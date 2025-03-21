# Maintainer: Seu Nome <seu@email.com>
pkgname=akrata-icon-theme
pkgver=20250321
pkgrel=1
pkgdesc="Cyberpunk themed icons for dark themes"
arch=("any")
url="https://github.com/Akr4ta/$pkgname"
license=("GPL3")
depends=(papirus-icon-theme)
source=("git+$url.git")
sha256sums=("SKIP")

package() {
    cd "$srcdir/$pkgname"
    install -dm755 "$pkgdir/usr/share/icons/"
    cp -r akrata-icons-anarchy "$pkgdir/usr/share/icons/"
    cp -r akrata-icons "$pkgdir/usr/share/icons/"
}
