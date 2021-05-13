[![QDataVis](doc/logo50percent.png)](https://github.com/jondef/QDataVis)

[Download](https://github.com/jondef/QDataVis#-download) |
[Feedback](https://github.com/jondef/QDataVis#%EF%B8%8F-feedback)

![GitHub labels](https://img.shields.io/badge/Version-v1.0.0-blue)
![GitHub labels](https://img.shields.io/badge/Language-C++-orange)
![GitHub](https://img.shields.io/github/license/jondef/QDataVis)
![GitHub repo size](https://img.shields.io/github/repo-size/jondef/QDataVis)
![Maintenance](https://img.shields.io/maintenance/yes/2021)
![GitHub labels](https://img.shields.io/badge/Ask%20me-anything-blue)

QDataVis is a simple to use, UI based, interactive plotter powered by <img src="https://cdn2.hubspot.net/hubfs/149513/Qt2017TemporaryImagesWebsite/qt_logo_with_text_green_rgb.png" height="15"/>.

  - Includes a mathematical expression parser written by me :)
  - Ability to use OpenGL for rendering
  - Plot and visualise functions
  - Plot datasets
  - Dark mode

🚀 Features
-----------
  - Plot cursor
  - Stick tick labels to the zero on the axes
  - Save your plots as PNG, JPG, etc...
  - Configure plot aesthetics
  - Plot single data points

🖼️ Screenshot
----------
![QDataVis](doc/screenshot.png)

💾 Download
--------
Pre-built executables for Windows, macOS, and Linux are found on the [Releases](https://github.com/jondef/QDataVis/releases) page.

⚙️ Building from source
----------
To build QDataVis from source, you'll need:
* [Qt6] - v6.1.0+ installed and included in PATH
* [CMake] - v3.17+
----------

1. Clone the repository
```sh
git clone --recurse-submodules https://github.com/jondef/QDataVis.git
```
2. Load the CMake project and compile!
```sh
cmake ./QDataVis && make ./QDataVis/build
```

❤️ Feedback
--------
Found a bug? Got suggestions? [Create an issue](https://github.com/jondef/QDataVis/issues/new)!

📝 License
-------
Apache 2.0

[Qt6]: <https://www.qt.io/>
[QCustomPlot]: <https://www.qcustomplot.com/>
[CMake]: <https://cmake.org/download/>
