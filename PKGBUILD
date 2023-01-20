pkgname=live-settings-blend
pkgver=1.0
pkgrel=1
pkgdesc='Default settings for live session'
url='https://github.com/blend-os/live-settings-blend'
arch=('any')
license=('Public domain')
source=('50_blend-settings.gschema.override')
sha256sums=('e06ade9649d5e3f0cd25110edd59a11cabfc956560cf7d4c25c5c2bc43562533')

package() {
	cd "$pkgdir"

	install -m644 "$srcdir"/50_blend-settings.gschema.override usr/share/glib-2.0/schemas/
}
