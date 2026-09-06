Mandelbulber 2.34 — Debian/Ubuntu amd64 package

Community-built Debian package for Mandelbulber 2.34 on 64-bit Debian/Ubuntu-based systems.

This repository is not the official Mandelbulber2 repository. It provides a repackaged .deb built from the Mandelbulber 2.34 Linux/portable distribution, with the program data included in the package and a desktop launcher and application icon.

What's included
Mandelbulber 2.34
amd64 Linux executable
Mandelbulber program data, formulas, examples, textures and OpenCL resources
Desktop application launcher
Application icon
No separate mandelbulber2-data package is required
Installation

Download the .deb package from the Releases section and install it with:

sudo apt install ./mandelbulber2-2.34-1_amd64.deb


If the package has been downloaded to another directory, replace the path accordingly.

Verify the download

After downloading the package:

sha256sum mandelbulber2-2.34-1_amd64.deb


Expected SHA-256:

bf240564f699d3c2bc4e9fbe48bb62b0a5ec73f52be80efd9f9b32c430a6209c

Package details
Package: mandelbulber2
Version: 2.34-1
Architecture: amd64
Program data directory: /usr/share/mandelbulber2/
Executable: /usr/bin/mandelbulber2
Desktop launcher: /usr/share/applications/mandelbulber2.desktop
Compatibility

This package was built and tested on a Debian/Ubuntu-family 64-bit Linux system.

The package declares its required runtime libraries through Debian package dependencies. Compatibility with other distributions is not guaranteed.

Important

This is a community packaging project and is not an official release of the Mandelbulber2 project.

Mandelbulber2 upstream:
https://github.com/buddhi1980/mandelbulber2

The original project, source code and included resources remain subject to their respective licenses and copyrights. Please consult the upstream project for the authoritative source code, licensing information and official releases.

License

The Mandelbulber2 project is distributed under the GNU General Public License version 3 or later where applicable. Some bundled resources and example collections may have additional or different licensing terms.

This repository does not replace the original project's license or copyright notices.
