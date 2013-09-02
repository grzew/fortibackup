all:

install:
	install -dm755 "$(DESTDIR)$(PREFIX)/bin/"
	install -m 755 "fortibackup" "$(DESTDIR)$(PREFIX)/bin/"

uninstall:
	rm "$(PREFIX)/bin/fortibackup"
	rmdir --ignore-fail-on-non-empty "$(PREFIX)/bin/"
