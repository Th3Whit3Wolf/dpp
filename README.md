# DPP (WIP) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

![Python](https://img.shields.io/badge/python-v3.6+-blue.svg)
![GitHub Contributors](https://img.shields.io/github/contributors/TheWhiteWolf1337/dpp.svg)
[![GitHub Issues](https://img.shields.io/github/issues/TheWhiteWolf1337/DPP.svg)](https://github.com/TheWhiteWolf1337/dpp/issues)
![GitHub Code Size](https://img.shields.io/github/languages/code-size/TheWhiteWolf1337/dpp.svg)
![GitHub Top Language](https://img.shields.io/github/languages/top/TheWhiteWolf1337/dpp.svg)
![GitHub Language Count](https://img.shields.io/github/languages/count/TheWhiteWolf1337/dpp.svg)
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)
[![GitHub License](https://img.shields.io/github/license/TheWhiteWolf1337/dpp.svg)](https://github.com/TheWhiteWolf1337/dpp/blob/master/LICENSE)

<h3 align="center">
    <a href="https://github.com/TheWhiteWolf1337/DPP/wiki">Wiki</a> |
    <a href="https://github.com/TheWhiteWolf1337/DPP/blob/master/CONTRIBUTING.md">Contributing</a> |
    <a href="https://github.com/TheWhiteWolf1337/DPP/wiki/FAQ">FAQ</a>
</h3>

## Objective

DPP is based on the design of yaourt, apacman and pacaur. It is developed with these objectives in mind:

- Download files in parallel
- Display progress similliar to dnf
- Provide an interface for pacman
- Yaourt-style interactive search/install
- Minimal dependencies
- Minimize user input
- Know when git packages are due for upgrades

## Features

- WIP

## Goals

- [ ] Perform advanced dependency solving
- [ ] Download PKGBUILDs from ABS or AUR
- [ ] Tab-complete the AUR
- [ ] Query user up-front for all input (prior to starting builds)
- [ ] Narrow search terms (yay linux header will first search linux and then narrow on header)
- [ ] Find matching package providers during search and allow selection
- [ ] Remove make dependencies at the end of the build process
- [ ] Run without sourcing PKGBUILD
- [ ] Install via makepkg

## Installation

Not in a working state
In the future dpp will be installed via

```sh
git clone https://github.com/TheWhiteWolf1337/dpp.git
cd dpp
makepkg -si
```

## Support

All support related to dpp should be requested via GitHub issues. Since dpp is not officially supported by Arch Linux, support should not be sought out on the forums, AUR comments or other official channels.

A broken AUR package should be reported as a comment on the package's AUR page. A package may only be considered broken if it fails to build with makepkg. Reports should be made using makepkg and include the full output as well as any other relevant information. Never make reports using Yay or any other external tools.

## Contributing

[contributing]: #contributing

Contributors are always welcome!

We would recommend starting with [issues](https://github.com/TheWhiteWolf1337/DPP/issues)

If you plan to make any large changes or changes that may not be 100% agreed on, we suggest opening an issue detailing your ideas first.

Otherwise check out [Contributing](CONTRIBUTING.md), send us a pull request, and we will be happy to review it.

### Depends

dpp depends on:

- python 3
- git
- base-devel

## License

[license]: #license

dpp is distributed under the terms of the GNU GENERAL PUBLIC LICENSE Version 3
Please see [license](LICENSE) if you have questions regarding what this includes.

## Authors

To see the list of authors, use this command inside pikaur git repository directory:

```sh
git log --pretty=tformat:"%an <%ae>" | sort -u
```
