# Galician Roads, Trams & Vehicles (GALVET)
[![GitHub license][license-shield]][license-url] [![BaNaNaS URL][bananas-shield]][bananas-url]

![Galician Roads, Trams & Vehicles (GALVET)](https://i.imgur.com/rK4ZdOV.png)

<!-- TABLE OF CONTENTS, generated with gh-md-toc README.md (see #acknowledgements) -->

Table of Contents
=================

* [Galician Roads, Trams &amp; Vehicles (GALVET)](#galician-roads-trams--vehicles-galvet)
* [Table of Contents](#table-of-contents)
   * [About The Project](#about-the-project)
   * [Getting Started](#getting-started)
      * [Requirements](#requirements)
      * [Installation](#installation)
      * [How to Compile it (from Linux)](#how-to-compile-it-from-linux)
   * [Usage](#usage)
   * [Support &amp; Contributing](#support--contributing)
   * [Authors](#authors)
   * [Acknowledgements](#acknowledgements)
   * [License](#license)

<!-- ABOUT THE PROJECT -->

## About The Project

Set of Roads, Trams & Road Vehicles for GalizaTTD.


<!-- GETTING STARTED -->
## Getting Started
### Requirements

- OpenTTD (<http://www.openttd.org>).

### Installation

- Download it through the integrated content manager in the game or through [BaNaNaS](http://bananas.openttd.org)
- You may also [manual install it](https://wiki.openttd.org/en/Manual/NewGRF#manual-install), download or compile the `.grf` and put it on the OpenTTD `newgrf` directory.

### How to Compile it (from Linux)

- [Install NML with its requirements](http://newgrf-specs.tt-wiki.net/wiki/NML:Getting_started)
- Download last version from this repository <https://github.com/GalizaTTD/galician-roads>
- "pandoc" command is used to generate txt docs from github docs (LICENSE, CHANGELOG & README)
- In order to compile the NewGRF you only need to execute `make` command.
- You can install it directly on the game customizing `INSTALL_DIR` on `Makefile.config` and running `make install`.

<!-- USAGE EXAMPLES -->
## Usage

- Once installed, choose parameters that best suit your needs and start a new game.

![Available Roads](https://i.imgur.com/Aaxqk1p.png)

<!-- CONTRIBUTING -->

## Support & Contributing

If you want to add any missing feature or report a bug, you [can request ir or report it here][issues-url]. Also if you are want and know how to do it, go ahead! That's what make the open source community shines, by allowing us to grow and learn from each other creating amazing tools! Any contribution you make is **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Authors

- Pablo Villaverde Castro - [@clankirfed](https://twitter.com/clankirfed)
- OpenGFX(RoadTunnels) - https://github.com/OpenTTD/OpenGFX
- Andrew350 ([RaTTRoads](https://www.tt-forums.net/viewtopic.php?t=76183))
- Ubify ([URaTT](https://github.com/Ufiby/U-RaTT))
- Supermop ([Flumes](https://www.tt-forums.net/viewtopic.php?style=4&f=67&t=88702))


<!-- ACKNOWLEDGEMENTS -->

## Acknowledgements
* [NML Tutorial](https://newgrf-specs.tt-wiki.net/wiki/NML:Main)
* [NML Town Names Docs](https://newgrf-specs.tt-wiki.net/wiki/NML:Town_names)
* [TOC Generator](https://github.com/ekalinin/github-markdown-toc)
* [MakeFile Tutorial](https://makefiletutorial.com/)


## License


[![GitHub license][license-shield]][license-url]

Distributed under the GNU GPL-v3 License. See [LICENSE][license-url] on for more information.


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[license-shield]: https://img.shields.io/badge/license-GNU%20GPL--v3-brightgreen
[bananas-shield]: https://img.shields.io/badge/BaNaNaS-1.0.1-informational
[license-url]: https://github.com/GalizaTTD/galician-roads/blob/main/LICENSE
[project-url]: https://github.com/GalizaTTD/galician-roads
[issues-url]: https://github.com/GalizaTTD/galician-roads/issues
[bananas-url]: https://bananas.openttd.org/manager/newgrf/4b463034