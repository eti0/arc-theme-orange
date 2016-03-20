#Quick install guide

To install you'll need:
* `autoconf`
* `automake`
* `pkg-config` or `pkgconfig` if you use Fedora
* `libgtk-3-dev` for Debian based distros or `gtk3-devel` for RPM based distros
* `git` if you want to clone the source directory

Run:

`./autogen.sh --prefix=/usr`

`sudo make install`

For troubleshooting please refer to "README.md".
