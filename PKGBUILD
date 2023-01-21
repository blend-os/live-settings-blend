pkgname=live-settings-blend
pkgver=1.0
pkgrel=1
pkgdesc='Default settings for live session'
url='https://github.com/blend-os/live-settings-blend'
arch=('any')
license=('Public domain')
source=('50_blend-settings.gschema.override'
        'installer-autostart.desktop')
sha256sums=('e06ade9649d5e3f0cd25110edd59a11cabfc956560cf7d4c25c5c2bc43562533'
            'dcc78ca9b6bd451ba43c891559c81bcf75a667ea81638fb4f10fdec117b44704')

package() {
	mkdir -p "$pkgdir"/usr/share/glib-2.0/schemas/; cp "$srcdir"/50_blend-settings.gschema.override "$pkgdir"/usr/share/glib-2.0/schemas/
	mkdir -p "$pkgdir"/etc/xdg/autostart/; cp "$srcdir"/installer-autostart.desktop "$pkgdir"/etc/xdg/autostart/
}
