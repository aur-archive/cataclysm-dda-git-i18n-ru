# Contributor: Ufo28 <ufo28x50 @t gmail dot com>
 
pkgname=cataclysm-dda-git-i18n-ru
pkgver=20150102
pkgrel=1
pkgdesc="Russian language pack for cataclysm-dda-git"
arch=('any')
license=('CCPL:by-sa')
install="cataclysm_ru.install"
url="http://www.seamonkey-project.org/"
depends=("cataclysm-dda-git>=0.B")
source=('http://heresy.soapfire.ru/cataclysm-dda/data/ru/master/latest.tar.gz' 'cataclysm_ru.install')
md5sums=('SKIP' '0404810891a12c72d5a0fcf215cb609e')

package() {
  cd "${srcdir}"
  local _instdir="/usr/share/cataclysm-dda"
  install -dm755 -g games "$pkgdir/${_instdir}/lang/"
  cp -r lang/* "$pkgdir/${_instdir}/lang"
}
