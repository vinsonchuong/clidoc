depends=('bash-common-parse-options' 'ruby-ronn' 'xidel')
makedepends=()

build() {
	cd "$srcdir/$pkgname-$pkgver-$pkgrel"
	[ -d 'doc' ] && bin/clidoc doc/*.md
}
