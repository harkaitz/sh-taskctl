DESTDIR =
PREFIX  =/usr/local


all:
clean:
install:
update:
## -- install-sh --
install: install-sh
install-sh:
	@mkdir -p $(DESTDIR)$(PREFIX)/bin
	@echo 'I bin/taskrun'   ; cp bin/taskrun     $(DESTDIR)$(PREFIX)/bin
	@echo 'I bin/taskctl'   ; cp bin/taskctl     $(DESTDIR)$(PREFIX)/bin
	@echo 'I bin/scron-run' ; cp bin/scron-run   $(DESTDIR)$(PREFIX)/bin
## -- install-sh --
## -- license --
install: install-license
install-license: LICENSE
	@echo 'I share/doc/sh-taskctl/LICENSE'
	@mkdir -p $(DESTDIR)$(PREFIX)/share/doc/sh-taskctl
	@cp LICENSE $(DESTDIR)$(PREFIX)/share/doc/sh-taskctl
## -- license --
