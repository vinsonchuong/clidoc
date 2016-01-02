depends=('bash-common-parse-options' 'ruby-ronn' 'xidel')
makedepends=()

build() {
	cd "$srcdir/$pkgname-$pkgver"
	[ -d 'doc' ] && bin/clidoc doc/*.md
}
