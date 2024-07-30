# Maintainer: Rohit Goswami (HaoZeke) <rohit.goswami@aol.com>
pkgname=autofirma-rpm
pkgver="1.8.3"
pkgrel=1
epoch=
pkgdesc="Autofirma es una aplicación de firma realizada por el Ministerio de Hacienda y Administraciones Públicas. Su principal objetivo es ofrecer al usuario un sistema de firma en el que éste pueda firmar cualquier tipo de documento de manera sencilla."
arch=('x86_64')
url="https://firmaelectronica.gob.es/Home/Ciudadanos/Aplicaciones-Firma.html#autofirma"
license=('EUPL')
groups=()
depends=('nss')
provides=('autofirma')
# conflicts=('')
options=('!strip' '!emptydirs')
makedepends=()
checkdepends=()
optdepends=()
replaces=()
backup=()
options=()
install=
changelog=
# source=("https://estaticos.redsara.es/comunes/autofirma/1/8/3/AutoFirma_Linux_Fedora.zip")
# md5sums=('5912736e1ce61e708fa00433abf31410')
source=("autofirma-1.8.3-1.noarch_FEDORA.rpm")
md5sums=('7933cc1a62cd0887ce2c4a954aea9306')
noextract=()                             

package() {
  # cd "$srcdir/"
  mv usr/lib64 usr/lib
  cp -rf usr ${pkgdir}
  # find $srcdir/ -mindepth 1 -maxdepth 1 -type d | xargs cp -r -t "$pkgdir"
}

# vim:set ts=2 sw=2 et:
