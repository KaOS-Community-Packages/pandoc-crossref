pkgname=pandoc-crossref
pkgver=0.3.9.0a
pkgrel=1
pkgdesc='Pandoc filter for cross-references.'
arch=('x86_64')
url='https://lierdakil.github.io/pandoc-crossref/'
license=('GPL-2.0')
depends=('pandoc')
makedepends=()
source=("https://github.com/lierdakil/pandoc-crossref/releases/download/v${pkgver}/pandoc-crossref-Linux.tar.xz")
md5sums=('64e1c596959987bfa7dd0c23a062dc47')

src_name="pandoc-${pkgver}"

build() {
    echo "No building is actually needed"
}

package() {
    install -Dm 755 "pandoc-crossref" "${pkgdir}/usr/bin/pandoc-crossref"
}
