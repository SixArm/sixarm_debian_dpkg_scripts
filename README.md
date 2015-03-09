# Debian » <br> Package utilities for dpkg command

We build custom debian packages for our servers and desktops.

These utility scripts help us.

## Query packages

* <code>dpkg-query-show</code>: Query and show with prettier output. 
* <code>dpkg-query-show-tsv</code>: Run dpkg-query with tab separated format of our favorite fields.
* <code>dpkg-list-debian-control-depends</code>: Print aggregated dependencies of our custom packages to an HTML list.

## Edit docs in a package

* <code>dpkg-gunzip-docs</code>: Run gunzip on all our the dpkg doc files in our custom package.
* <code>dpkg-gzip-docs</code>: Run gzip on all our the dpkg doc files in our custom package.
* <code>dpkg-edit-docs</code>: Start our editing of a custom package's docs.
* <code>dpkg-edited-docs</code>: End our editing of a custom package's docs.

## Publish all our packages

* <code>dpkg-publish</code>: Publish our deb packages to our local host and remote host.
* <code>dpkg-publish-to-local</code>: Debian packaging utility to publish our custom packages.
* <code>dpkg-publish-to-remote</code>: Sync the local debian repository to our remote.

## Misc

* <code>dpkg-clone</code>: Clone a new Debian package (i.e. dpkg deb file) with renaming.
* <code>dpkg-scan</code>: Scan packages and scan sources to create .gz file
* <code>dpkg-build</code>: Build a debian package via dpkg-deb and verify via lintian.
* <code>dpkg-install-ad-hoc</code>: Install all the sixarm debian packages ad hoc by using grep and xargs.
* <code>dpkg-snippets.txt</code>: Snippets to help create debian packages

