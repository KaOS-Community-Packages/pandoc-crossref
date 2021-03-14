pkgname=pandoc-crossref
pkgver=0.3.10.0
pkgrel=1
pkgdesc='Pandoc filter for cross-references.'
arch=('x86_64')
url='https://lierdakil.github.io/pandoc-crossref/'
license=('GPL-2.0')
depends=('pandoc')
makedepends=()
source=("https://github.com/lierdakil/pandoc-crossref/releases/download/v${pkgver}/pandoc-crossref-Linux.tar.xz")
md5sums=('98a3e8cfe355f48c010d31defc0cffd6')

package() {
    install -Dm 755 "pandoc-crossref" "${pkgdir}/usr/bin/pandoc-crossref"
}
