Mandelbulber 2 is a 3D fractal renderer and generator developed by the Mandelbulber Team.

Important: This repository is not the official Mandelbulber2 repository and this package is not an official Mandelbulber release package.

This project provides a repackaged .deb built from the Mandelbulber 2.34 Linux/portable distribution, with the program data included in the package together with a desktop launcher and application icon.

---

✨ What's included
Mandelbulber 2.34
Native amd64 / x86_64 Linux executable
Mandelbulber program data
Fractal formulas and UI resources
Example .fract files
Textures and application resources
OpenCL-related resources included with the distribution
Desktop application launcher
Application icon
Correct application-menu integration
Complete application data included in the .deb
No separate mandelbulber2-data package required

---

🖥️ System requirements
Requirement	Value
Architecture	amd64 / x86_64
Package format	Debian .deb
Target systems	Debian / Ubuntu and compatible derivatives
Mandelbulber version	2.34
OpenCL	Supported through the system OpenCL runtime
Package size	~58 MB

---

📦 Installation

Download the latest .deb package from the Releases section.

Then install it with:

sudo apt install ./mandelbulber2-2.34-1_amd64.deb


If the package was downloaded to another directory, replace the path accordingly.

After installation, Mandelbulber should also appear in the desktop application menu.

You can launch it from the menu or with:

mandelbulber2

---

🔐 Verify the download

The SHA-256 checksum of the published package is:

bf240564f699d3c2bc4e9fbe48bb62b0a5ec73f52be80efd9f9b32c430a6209c


Verify the downloaded file with:

sha256sum mandelbulber2-2.34-1_amd64.deb


The resulting checksum should match the value above.

A copy of the checksum is also provided in SHA256SUMS.

---

🚀 Launch

After installation:

mandelbulber2


Alternatively, launch Mandelbulber v2 from the desktop application menu.

---

🧹 Uninstallation

Remove the package with:

sudo apt remove mandelbulber2


To remove the package and its automatically installed dependencies that are no longer required:

sudo apt autoremove

---

🧩 OpenCL

Mandelbulber can use OpenCL through the system OpenCL runtime.

The package includes the OpenCL-related application resources from the Mandelbulber 2.34 distribution, but the appropriate OpenCL driver/runtime for your GPU must be provided by the operating system.

For NVIDIA, AMD or Intel GPUs, install the appropriate vendor-supported driver and OpenCL runtime for your Linux distribution.

---

📁 Package contents

The package installs the main executable at:

/usr/bin/mandelbulber2


Application data is installed under:

/usr/share/mandelbulber2/


The desktop launcher is installed at:

/usr/share/applications/mandelbulber2.desktop


The application icon is installed at:

/usr/share/icons/hicolor/128x128/apps/mandelbulber2.png

---

📋 Package information
Package:       mandelbulber2
Version:       2.34-1
Architecture:  amd64
Format:        Debian .deb
Size:          ~58 MB

---

⚠️ Important

This is an unofficial community package.

It is not affiliated with, maintained by, or endorsed by the official Mandelbulber Team.

The package was created by repackaging the Mandelbulber 2.34 Linux/portable distribution into a self-contained Debian package for amd64.

The original Mandelbulber project and its authors retain their respective copyrights and licenses.

Please consult the original Mandelbulber project for source code, official releases, documentation and licensing information.

---

📜 Credits
Mandelbulber Team — Mandelbulber 2
Community packaging — thaurock-x
Included example collections and other third-party resources remain subject to their respective licenses and attribution requirements.

---

🤝 Community

This repository exists to make Mandelbulber 2.34 easier to install on compatible Debian/Ubuntu-based systems.

Issues and suggestions regarding this community package are welcome through the GitHub issue tracker.

---

📥 Download

Go to the latest GitHub Release:

Mandelbulber 2.34-1 — Latest Release

Download:

mandelbulber2-2.34-1_amd64.deb


and optionally:

SHA256SUMS

Man
delbulber 2.34 — Community Debian/Ubuntu amd64 package

---

By THAUROCK
