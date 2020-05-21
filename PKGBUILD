# Maintainer: Alfredo Ramos <alfredo dot ramos at yandex dot com>
# Contributor: Thomas Nordenmark <t.nordenmark@gmail.com>

pkgname=prootrun
pkgver=1
pkgrel=1
arch=('any')
license=('GPL3')

depends=('proot')

source=("prootrun"
)

sha256sums=(
	'SKIP'
)


package() {
	install -d "${pkgdir}"/usr/bin/
	install -m755 "${srcdir}"/prootrun "${pkgdir}"/usr/bin/
}
