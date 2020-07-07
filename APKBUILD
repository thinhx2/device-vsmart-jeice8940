# Reference: <https://postmarketos.org/devicepkg>
pkgname=device-vsmart-jeice8940
pkgdesc="Joy 1"
pkgver=0.1
pkgrel=6
url="https://postmarketos.org"
license="MIT"
arch="armhf"
options="!check !archcheck"
depends="postmarketos-base linux-vsmart-jeice8940 mkbootimg mesa-dri-swrast msm-fb-refresher"
makedepends="devicepkg-dev"
source="deviceinfo"

build() {
	devicepkg_build $startdir $pkgname
}

package() {
	devicepkg_package $startdir $pkgname
}

sha512sums="8914ef0b373f2c1eef292d0f72958f532f5e9bd4ed41d9fc140387e028d62df1ddc899af4cadd74b6de2d55e9bc351c68e418e90ebdb526741543e70fa27b0e6  deviceinfo"
