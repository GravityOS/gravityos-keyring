# Maintainer: Ethan Lane <ethan@vylpes.com>

pkgname=gos-keyring
pkgver=20211223
pkgrel=1
pkgdesc='GravityOS PGP keyring'
arch=(any)
url='https://github.com/gravityos'
license=(MIT)
install=gos-keyring.install
source=('gos.gpg' 'gos-revoked' 'gos-trusted')
sha256sums=('SKIP'
            'SKIP'
            'SKIP')

package() {
  install -Dm 644 gos.gpg "$pkgdir"/usr/share/pacman/keyrings/gos.gpg
  install -Dm 644 gos-revoked "$pkgdir"/usr/share/pacman/keyrings/gos-revoked
  install -Dm 644 gos-trusted "$pkgdir"/usr/share/pacman/keyrings/gos-trusted
}
