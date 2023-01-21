DESTDIR =
PREFIX  =/usr/local


all:
clean:
install:
update:
## -- install-sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/git-h-update-submodules $(DESTDIR)$(PREFIX)/bin
	cp bin/projectm-github  $(DESTDIR)$(PREFIX)/bin
	cp bin/git-traverse     $(DESTDIR)$(PREFIX)/bin
	cp bin/git-h-delete     $(DESTDIR)$(PREFIX)/bin
	cp bin/projectm         $(DESTDIR)$(PREFIX)/bin
	cp bin/github-h-desc    $(DESTDIR)$(PREFIX)/bin
	cp bin/git-ssh          $(DESTDIR)$(PREFIX)/bin
	cp bin/github-h-url     $(DESTDIR)$(PREFIX)/bin
	cp bin/projectm-github-page $(DESTDIR)$(PREFIX)/bin
	cp bin/git-h-ls-submodules $(DESTDIR)$(PREFIX)/bin
	cp bin/git-h-sync       $(DESTDIR)$(PREFIX)/bin
	cp bin/git-h-get-branch $(DESTDIR)$(PREFIX)/bin
	cp bin/git-h-my-branch  $(DESTDIR)$(PREFIX)/bin
	cp bin/git-h-ls-branches $(DESTDIR)$(PREFIX)/bin
## -- install-sh --
## -- license --
install: install-license
install-license: LICENSE
	mkdir -p $(DESTDIR)$(PREFIX)/share/doc/sh-git-helpers
	cp LICENSE $(DESTDIR)$(PREFIX)/share/doc/sh-git-helpers
## -- license --
