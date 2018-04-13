# Maintainer: P3p1t0 (https://github.com/P3p1t0/pokemonsay-archbased)
# Feel free to maintain pokemonsay-package on AUR if you want

pkgname=pokemonsay-package
pkgver=00000000
pkgrel=1
pkgdesc='Cowsay, but with Pokemons'
arch=('any')
url='https://github.com/P3p1t0/pokemonsay-packagefriendly'
license=('MIT')
options=('!strip')
depends=('cowsay')
optdepends=('cowfortune: For fortune cookies')
source=("https://github.com/P3p1t0/pokemonsay-packagefriendly/releases/download/00000000/pokemonsay-packagefriendly-$pkgver.zip")
sha512sums=('366757660fc17e93bf5d2a7f8045d6bfaae9cb1cdac323cb34d033ad3a60ae529ebaa037201b9a9c1240761ca7d0e863a5fc1031f67771947dfe0fe4058fe700')

package() {

	cp -dr --no-preserve=ownership "${srcdir}"/$pkgname-packagefriendly/{opt,usr} "${pkgdir}"/
    install -Dm644 "${srcdir}"/pokemonsay-packagefriendly/LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"

}
