# Maintainer: holmeslinux <holmes_holmes@live.com>

pkgname=pacli-jwm
pkgver=0.1
pkgrel=2
pkgdesc="an interactive pacman interface using pmenu"
arch=(any)
url="https://github.com/holmeslinux/$pkgname"
license=(GPL2)
depends=('bash'
	'downgrade'
	'gzip'
	'pacman'
	'pacman-mirrorlist'
	'pmenu'
	'sudo'
	'yaourt')
makedepends=('git')
conflicts=('pacli')
provides=('pacli')
optdepends=('update-notifier: Automatically get notified when updates are available')
source=("git://github.com/holmeslinux/$pkgname")
md5sums=('SKIP')

package () {
    install -Dm755 "$pkgname/$pkgname" "$pkgdir/usr/bin/pacli"
}