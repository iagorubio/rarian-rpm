# rarian-rpm

This project aims to provide patches and specs for a rpm build of librarian

Full source of librarian is at https://rarian.freedesktop.org/Releases/rarian-0.8.1.tar.bz2

Rarian Website https://rarian.freedesktop.org/

To build the rpm copy the tar file and patches to your rpmbuild sorces dir, usually:

~/rpmbuild/SOURCES

Use the command *rpmbuild -ba rarian.spec* to build the rpm.

The resulting rpm will be at your rpmbuild RPM directory and the source rpms at the SRPMS
directory, usually:

~/rpmbuild/RPMS
~/rpmbuild/SRPMS

