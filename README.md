# Debian Packages » Builder scripts

We build Debian packages for our systems.

These scripts help us with our workflow.

## Query packages

* `dpkg-query-show`: Query and show with prettier output.
* `dpkg-query-show-tsv`: Run dpkg-query with tab separated format of our favorite fields.
* `dpkg-list-debian-control-depends`: Print aggregated dependencies of our custom packages to an HTML list.

## Edit docs in a package

* `dpkg-gunzip-docs`: Run gunzip on all our the dpkg doc files in our custom package.
* `dpkg-gzip-docs`: Run gzip on all our the dpkg doc files in our custom package.
* `dpkg-edit-docs`: Start our editing of a custom package's docs.
* `dpkg-edited-docs`: End our editing of a custom package's docs.

## Publish all our packages

* `dpkg-publish`: Publish our deb packages to our local host and remote host.
* `dpkg-publish-to-local`: Debian packaging utility to publish our custom packages.
* `dpkg-publish-to-remote`: Sync the local debian repository to our remote.

## Misc

* `dpkg-clone`: Clone a new Debian package (i.e. dpkg deb file) with renaming.
* `dpkg-scan`: Scan packages and scan sources to create .gz file
* `dpkg-build`: Build a debian package via dpkg-deb and verify via lintian.
* `dpkg-install-ad-hoc`: Install all the sixarm debian packages ad hoc by using grep and xargs.
* `dpkg-snippets.txt`: Snippets to help create debian packages
