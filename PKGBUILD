# Maintainer: P3p1t0 (https://github.com/P3p1t0/pokemonsay-archbased)
# Feel free to maintain pokemonsay-package on AUR if you want

pkgname=pokemonsay-archbased
pkgver=20171228
pkgrel=1
pkgdesc='Cowsay, but with Pokemons'
arch=('any')
url='https://github.com/P3p1t0/pokemonsay-packagefriendly'
license=('MIT')
options=('!strip')
depends=('cowsay')
optdepends=('cowfortune: For fortune cookies')
source=("https://github.com/P3p1t0/pokemonsay-packagefriendly/releases/download/$pkgver/pokemonsay-packagefriendly-$pkgver.zip")
sha512sums=('f22bf991cb155470ca1433605e61478e355e8bc509bf3644509f8864883a532f0ce8db705ebb78430192dddb18dfdee426202efb2ca08af82ebe6ec1e6cfa8b2')

package() {

	cp -dr --no-preserve=ownership "${srcdir}"/pokemonsay-packagefriendly/{opt,usr} "${pkgdir}"/
    install -Dm644 "${srcdir}"/pokemonsay-packagefriendly/LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"

}
