# Maintainer: holmeslinux <holmes_holmes@live.com>

pkgname=pacli-jwm
pkgver=0.1
pkgrel=1
pkgdesc="an interactive pacman interface using pmenu"
arch=(any)
url="https://github.com/holmeslinux/$pkgname"
license=(GPL2)
depends=('pmenu'
	'pacman'
	'yaourt'
	'pacman-mirrorlist'
	'sudo'
	'gzip'
	'downgrade'
	'bash')
makedepends=('git')
optdepends=('update-notifier: Automatically get notified when updates are available')
source=("git://github.com/holmeslinux/$pkgname")
md5sums=('SKIP')

package () {
    install -Dm755 "$srcdir/$pkgname/pacli" "$pkgdir/usr/bin/pacli-jwm"
}