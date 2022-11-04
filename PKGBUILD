# Generated by debtap
# Maintainer: Will Furnass <w.furnass@sheffield.ac.uk>

pkgname=ronin-link-bin
_pkgname=ronin-link
pkgver=2.3.2
pkgrel=1
pkgdesc="A desktop app for linking to your machines securely in Ronin . A desktop app for linking to your machines securely in Ronin."
arch=('x86_64')
url="https://ronin.cloud"
license=('MIT')
groups=('')
depends=('alsa-lib' 'atk' 'at-spi2-atk' 'at-spi2-core' 'cairo' 'dbus' 'desktop-file-utils' 'discord' 'expat' 'gcc-libs' 'gdk-pixbuf2' 'glib2' 'glibc' 'gtk3' 'gvfs' 'hicolor-icon-theme' 'libcups' 'libnotify' 'libsecret' 'libx11' 'libxcb' 'libxcomposite' 'libxcursor' 'libxdamage' 'libxext' 'libxfixes' 'libxi' 'libxrandr' 'libxrender' 'libxss' 'libxtst' 'nspr' 'nss' 'pango' 'trash-cli' 'xdg-utils')
optdepends=('pulseaudio' 'alsa-lib')
options=('!strip' '!emptydirs')
install=${pkgname}.install
source_x86_64=("https://ronin.cloud/apps/${_pkgname}-${pkgver}.deb")
sha512sums_x86_64=('34811f561f8d46b3dbf569fa493343d43662792fbfb30d10daa54634eac947fe1cf1a122e2c33f607e9c01e8d50f83ddf15158b987412036ae4c6ab8acf76bf5')

package(){

	# Extract package data
	tar -xI zstd -f data.tar.zst -C "${pkgdir}"

        install -D -m644 "${pkgdir}/usr/lib/${_pkgname}/LICENSES.chromium.html" "${pkgdir}/usr/share/licenses/${_pkgname}/LICENSE.html"
	install -D -m644 "${pkgdir}/usr/share/doc/${_pkgname}/copyright" "${pkgdir}/usr/share/licenses/${_pkgname}/COPYRIGHT"

}

# depends with no equiv in Arch:
#            'kde-cli-tools' 'kde-runtime' 
# optdepends with no equiv in Arch:
#            'gir1.2-gnomekeyring-1.0'
