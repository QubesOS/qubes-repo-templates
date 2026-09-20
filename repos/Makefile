install:
	install -d $(DESTDIR)/etc/qubes/repo-templates
	install -d $(DESTDIR)/etc/qubes/repo-templates/keys
	install -m 0644 qubes-templates.repo $(DESTDIR)/etc/qubes/repo-templates/qubes-templates.repo
	install -m 0644 RPM-GPG-KEY-qubes-4.3-primary $(DESTDIR)/etc/qubes/repo-templates/keys/RPM-GPG-KEY-qubes-4.3-primary
	install -m 0644 RPM-GPG-KEY-qubes-4.3-templates-community $(DESTDIR)/etc/qubes/repo-templates/keys/RPM-GPG-KEY-qubes-4.3-templates-community
	install -m 0644 RPM-GPG-KEY-qubes-devel-primary \
		$(DESTDIR)/etc/qubes/repo-templates/keys/RPM-GPG-KEY-qubes-devel-primary
	install -m 0644 RPM-GPG-KEY-qubes-devel-templates-community \
		$(DESTDIR)/etc/qubes/repo-templates/keys/RPM-GPG-KEY-qubes-devel-templates-community
