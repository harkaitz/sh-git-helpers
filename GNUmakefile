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
	cp bin/git-h-delete     $(DESTDIR)$(PREFIX)/bin
	cp bin/git-h-config     $(DESTDIR)$(PREFIX)/bin
	cp bin/git-ssh          $(DESTDIR)$(PREFIX)/bin
## -- install-sh --
## -- license --
install: install-license
install-license: LICENSE
	mkdir -p $(DESTDIR)$(PREFIX)/share/doc/sh-git-helpers
	cp LICENSE $(DESTDIR)$(PREFIX)/share/doc/sh-git-helpers
## -- license --
