# Maintainer: lincore <dvl dot lincore at gmail dot com>
pkgname=greyness-gtk-theme
pkgver=2.1
pkgrel=2
pkgdesc="A grey GTK/Unity theme by CraazyT"
url="http://craazyt.deviantart.com/art/Greyness-GTK-Theme-v2-1-281037508"
license=('GPL3')
arch=('any')
depends=('gtk-engine-unico' 'gtk-engine-murrine' 'gtk3')
optdepends=('gnome-tweak-tool: Easy theme switcher')
source=('http://www.deviantart.com/download/281037508/greyness_gtk_theme_v2_1_by_craazyt-d4nblxg.zip')
md5sums=('060a870c44a5187d56313e3241813807')

package() {
    cd "$srcdir"
    mkdir -p "$pkgdir/usr/share/themes"
    mv "Greyness-GTK " "$pkgdir/usr/share/themes/Greyness"
    chmod 755 -R "$pkgdir/usr/share/themes/Greyness"
}