Mandelbulber 2.34 — Debian/Ubuntu amd64









Unofficial community Debian package for Mandelbulber 2.34.

Mandelbulber 2 is a 3D fractal renderer and generator developed by the Mandelbulber Team.

This repository provides a community-built .deb package for 64-bit Debian/Ubuntu-based Linux systems (amd64).

Important: This is not the official Mandelbulber2 repository or an official release package. It is a community repackaging of the Mandelbulber 2.34 Linux/portable distribution.

✨ What's included
Mandelbulber 2.34
Native amd64 Linux executable
Mandelbulber program data
Fractal formulas and UI resources
Example .fract files
Textures and other application resources
OpenCL-related resources included with the distribution
Desktop application launcher
Application icon
Correct application-menu integration
All required program data included in the .deb
No separate mandelbulber2-data package is required
🖥️ System
Requirement	Value
Architecture	amd64 / x86_64
Package format	Debian .deb
Target systems	Debian / Ubuntu and derivatives
Mandelbulber version	2.34
OpenCL	Supported through system OpenCL runtime
Package size	~58 MB
📦 Installation

Download the .deb package from the Releases section of this repository.

Then install it with:

sudo apt install ./mandelbulber2-2.34-1_amd64.deb


If the package is located somewhere else, replace the path accordingly.

After installation, Mandelbulber should also appear in the desktop application menu.

You can also launch it from a terminal:

mandelbulber2

🔐 Verify the download

A SHA-256 checksum is provided in SHA256SUMS.

After downloading the package, run:

sha256sum mandelbulber2-2.34-1_amd64.deb


The expected checksum for the current package is:

bf240564f699d3c2bc4e9fbe48bb62b0a5ec73f52be80efd9f9b32c430a6209c


You can also verify it automatically:

sha256sum -c SHA256SUMS


Expected result:

mandelbulber2-2.34-1_amd64.deb: OK

🧩 Package details

Package name:

mandelbulber2


Version:

2.34-1


Architecture:

amd64


The package includes the application data under:

/usr/share/mandelbulber2/


The executable is installed as:

/usr/bin/mandelbulber2


The desktop launcher is installed as:

/usr/share/applications/mandelbulber2.desktop


The application icon is installed under:

/usr/share/icons/hicolor/128x128/apps/mandelbulber2.png

🛠️ Why this package exists

The purpose of this repository is to provide a convenient Debian/Ubuntu package containing the Mandelbulber 2.34 application and its required program data in a single package.

This avoids the situation where the application is installed while the required mandelbulber2-data package or data files are missing.

The package also provides a desktop launcher and application icon so Mandelbulber can be launched normally from the graphical application menu.

⚠️ Unofficial community build

This package is maintained as a community build and is not affiliated with, endorsed by, or officially distributed by the Mandelbulber Team.

For the official Mandelbulber project, please refer to the project's official distribution channels.

Before installing software from any third-party repository, users should review the package contents and verify the provided checksum.

📜 Licensing

Mandelbulber and its included components are subject to their respective original licenses.

Some example files and resources included with Mandelbulber have their own attribution and licensing requirements.

This repository does not claim ownership of the original Mandelbulber software, formulas, examples, textures, artwork, or other upstream resources.

🤝 Community

If this package is useful to you:

⭐ Star the repository
🐛 Open an issue if you encounter a packaging problem
💡 Submit improvements or fixes
📢 Share the project with other Debian/Ubuntu Mandelbulber users
📥 Download

The recommended way to obtain the package is through the GitHub Releases section of this repository.

Package: mandelbulber2-2.34-1_amd64.deb

Architecture: amd64

Version: 2.34-1

Disclaimer

This project is an unofficial community packaging project. Mandelbulber 2 remains the work of its original developers and contributors.

No warranty is provided for this community-built package. Use it at your own discretion.
This repository does not replace the original project's license or copyright notices.
