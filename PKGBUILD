pkgname=wee-slack
pkgver=2.4.0
pkgrel=1
pkgdesc='A WeeChat plugin for Slack.com'
url='https://github.com/wee-slack/wee-slack/'
arch=('any')
license=('MIT')
depends=('weechat' 'python-websocket-client')
source=("${pkgname}_${pkgver}.tar.gz::https://github.com/wee-slack/wee-slack/archive/v${pkgver}.tar.gz")
sha512sums=('2e6d0f0555adc5eec143dd784d360e33c1a93b8cbab92931ee6778663ccc600e4d040d1e8492bc5085597893f6778b47c6f52a7a894c29c6ed796a323ff06d39')

package() {
  cd "$srcdir/$pkgname-$pkgver"
  install -Dm644 wee_slack.py ${pkgdir}/usr/lib/weechat/python/wee_slack.py
}

# vim:set ts=2 sw=2 et:
