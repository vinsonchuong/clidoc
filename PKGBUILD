depends=('ruby-ronn' 'xidel')

build() {
	cd "$srcdir/$pkgname-$pkgver"
	[ -d 'doc' ] && bin/clidoc doc/*.md
}
