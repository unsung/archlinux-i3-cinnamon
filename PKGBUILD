# Fork of the AUR awesome-cinnamon package, a fork of awesome-gnome
# Maintainer of awesome-cinnamon package:
# Maintainer: Claire Farron <diesal3@googlemail.com>
# Original maintainers of the awesome-gnome package -
# Maintainer: Rainux Luo <rainux@gmail.com>
# Contributor: Daniel Wallace <daniel.wallace12@gmail.com>

# Maintainer of i3-cinnamon:
#   Josh Manning <unsungmaster@gmail.com>

pkgname=i3-cinnamon
pkgver=0.1
pkgrel='1'
pkgdesc='Launch i3 with cinnamon-settings-daemon'
arch=('any')
url='https://github.com/unsung/archlinux-awesome-cinnamon'
license=('CCPL')
depends=('i3' 'cinnamon>=2.0' 'notification-daemon')
install=i3-cinnamon.install
source=($pkgname.desktop
        i3.desktop
        i3.session)
md5sums=('bd0f43bdf3fa971bfdf8fc7cbe07b0f4'
         '4e47a27bfb9b062dc714a4aeaaff7fa9'
         '5fe742ddb43b047add0d1bd3a0f25323')

package() {
    cd $srcdir
    install -Dm644 $srcdir/${source[2]} $pkgdir/usr/share/cinnamon-session/sessions/${source[2]}
    install -Dm644 $srcdir/${source[1]} $pkgdir/usr/share/applications/${source[1]}
    install -Dm644 $srcdir/${source[0]} $pkgdir/usr/share/xsessions/${source[0]}
}

# vim:set sts=2 ts=2 sw=2 et:
