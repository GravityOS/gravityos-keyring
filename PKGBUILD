# Maintainer: Ethan Lane <ethan@vylpes.com>

pkgname=gos-keyring
pkgver=20211223
pkgrel=1
pkgdesc='GravityOS PGP keyring'
arch=(any)
url='https://github.com/gravityos'
license=(MIT)
install=gos-keyring.install
source=('build/gos.gpg' 'build/gos-revoked' 'build/gos-trusted')
sha256sums=('SKIP'
            'SKIP'
            'SKIP')

package() {
  install -Dm 644 build/gos.gpg "$pkgdir"/usr/share/pacman/keyrings/gos.gpg
  install -Dm 644 build/gos-revoked "$pkgdir"/usr/share/pacman/keyrings/gos-revoked
  install -Dm 644 build/gos-trusted "$pkgdir"/usr/share/pacman/keyrings/gos-trusted
}
