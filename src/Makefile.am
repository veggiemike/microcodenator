dist_bin_SCRIPTS =
dist_bin_SCRIPTS += microcodenator

dist_sysconf_DATA =
dist_sysconf_DATA += microcodenator.conf

pkgdata_DATA =
pkgdata_DATA += microcodenator.sh


install-exec-hook:
	sed -i 's|__LIBDIR__|$(pkgdatadir)|' $(DESTDIR)$(bindir)/microcodenator
	sed -i 's|__CONFDIR__|$(sysconfdir)|' $(DESTDIR)$(bindir)/microcodenator
