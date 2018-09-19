# Maintainer: Jan Boelsche <jan@lagomorph.de>
pkgname=background-tile-curls
pkgver=1.0
pkgrel=1
pkgdesc="curls pattern from subtlepatterns.com"
arch=('any')
url="http://subtlepatterns.com"
license=('CC BY-SA 3.0')
provides=('background')
source=('curls.png')

sha256sums=('4815598698d8b19e1dd05aaeed4ee2a33d3b891b532a0a9f2d3f8f3f48e1cad4')

package() {
  src='curls.png'
  dir='/usr/share/backgrounds'
  fn='background-tile.png'

  install -Dm 644 -T "${src}" "${pkgdir}/${dir}/${fn}"
  ln -s "${dir}/${fn}" "${pkgdir}/${dir}/loading.png"
  ln -s "${dir}/${fn}" "${pkgdir}/${dir}/desktop.png"
}
