<div align="center">
  <img src="https://raw.githubusercontent.com/bottlesdevs/Bottles/master/data/icons/hicolor/scalable/apps/com.usebottles.bottles.svg" width="64">
  <h1 align="center">Bottles</h1>
  <p align="center">Easily manage wineprefix using environments</p>
</div>

<br/>

<div align="center">
  <a href="https://hosted.weblate.org/engage/bottles">
    <img src="https://hosted.weblate.org/widgets/bottles/-/bottles/svg-badge.svg" />
  </a>
  <a href="https://www.codefactor.io/repository/github/bottlesdevs/bottles/overview/master">
    <img src="https://www.codefactor.io/repository/github/bottlesdevs/bottles/badge/master" />
  </a>
  <a href="https://github.com/bottlesdevs/Bottles/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/License-GPL--3.0-blue.svg">
  </a>
  <a href="https://github.com/bottlesdevs/Bottles/actions">
    <img src="https://github.com/bottlesdevs/Bottles/workflows/Build%20release%20packages/badge.svg">
  </a>
  <a href="https://aur.archlinux.org/packages/bottles/">
    <img alt="AUR version" src="https://img.shields.io/aur/version/bottles">
  </a>
  <br>
  <a href="https://stopthemingmy.app" title="Please do not theme this app">
    <img src="https://stopthemingmy.app/badge.svg">
  </a>

  <hr />

  <a href="https://docs.usebottles.com">Documentation</a> ·
  <a href="https://forums.usebottles.com">Forums</a> · 
  <a href="https://t.me/usebottles">Telegram group</a> · 
  <a href="https://usebottles.com/funding">Funding</a>
</div>

<br/>

<div align="center">
  <img src="https://raw.githubusercontent.com/bottlesdevs/Bottles/master/screenshot.png">
</div>

## 📚 Documentation
Before opening a new issue, check if the topic has already been covered 
in our [documentation](https://docs.usebottles.com).

Please note that some pages of the documentation are still being written.

## 🗣 Help Bottles speak your language
Read [here](https://github.com/bottlesdevs/Bottles/tree/master/po#readme) how to 
translate Bottles in your language or how to help improve existing ones.

## 🦾 Features
- Create bottles based on environments (a set of rules and dependencies)
- Access to a customizable environment for all your experiments
- Automated installers
- Run every executable (.exe/.msi/.bat) in your bottles, using the context menu in your file manager
- Integrated management and storage for executable file arguments
- Support for custom environment variables
- Simplified DLL overrides
- Manage and install multiple wine/proton/dxvk versions and on-the-fly change
- Various optimizations for better gaming performance (esync, fsync, dxvk, cache, shader compiler, offload ... and much more.)
- Tweak different wine prefix settings, without leaving Bottles
- Automated dxvk installation
- System for checking runner updates for the bottle and automatic repair in case of breakage
- Integrated Dependencies installer with compatibility check based on a community-driven [repository](https://github.com/bottlesdevs/dependencies)
- Detection of installed programs
- Integrated Task manager for wine processes
- Easy access to ProtonDB and WineHQ for support
- Configurations update system across Bottles versions
- Backup and Import bottles from older version and from other managers (Lutris, POL, ..)
- Bottles versioning
- ... and much more that you can find by installing Bottles!

### 🚧 Work in progress
- Layers (dependencies and programs on different layers) [#510](https://github.com/bottlesdevs/Bottles/issues/510)

## ↗️ Install
Bottles is officially provided as Flatpak, AppImage, [AUR package](https://aur.archlinux.org/packages/bottles/). 
There are also other packages maintained by our community, like Fedora, 
[AUR (bottles-git)](https://aur.archlinux.org/packages/bottles-git/), [CachyOS AUR](https://github.com/CachyOS/linux-cachyos#we-are-providing-a-repo-which-includes-all-kernels-in-generic-v3-and-generic-and-more-optimized-packages), and MX Linux.

Read [here](https://docs.usebottles.com/getting-started/installation) how to
install Bottles on your distribution.

### Notices for package maintainers
We are happy to see packaged Bottles but we ask you to respect some small rules:
- The package must be `bottles`, in other distributions it is possible to use suffixes (e.g. `bottles-git` on Arch Linux for the git based package) while on others the RDNN format is required (e.g. `com.usebottles.bottles` on elementary OS and Flathub repository). All other nomenclatures are discouraged.
- Do not package external files and do not make changes to the code, no hard script. Obviously with the exception of files essential for packaging.
Once the package is published, you can open a [Pull Request](https://github.com/bottlesdevs/Bottles/pulls) to add it to the packages table above! Thanks :heart:!
- Package version should follow the CalVer model (year.month.day) and the release cycle of the project. Bottles has 2 released per month: one on 14th and one on 28th. When an hotfix came, this will be appended to the release (e.g. 2022.2.14-1). Bottles as a codename too which is not mandatory and currently only used by the Flatpak.

## Shortcuts
| Shortcut |         Action          |
|:--------:|:-----------------------:|
| `Ctrl+Q` |      Close Bottles      |
| `Ctrl+R` | Reload the Bottles list |
|   `F1`   | Go to the documentation |
|  `Esc`   |         Go back         |

## FAQ
- [Why Bottles?](https://docs.usebottles.com/faq/why-bottles)
- [Where is Winetricks?](https://docs.usebottles.com/faq/where-is-winetricks)
- [Older versions will be deprecated?](https://docs.usebottles.com/faq/updates-and-old-versions#older-versions-will-be-deprecated)
- [Backward compatibility?](https://docs.usebottles.com/faq/updates-and-old-versions#backward-compatibility)

## Sponsors
<a href="https://www.jetbrains.com/?from=bottles"><img height="55" src="https://unifiedban.solutions/static/images/jetbrains-logos/jetbrains.png" /></a>&nbsp;&nbsp;&nbsp;
<a href="https://www.gitbook.com/?ref=bottles"><img height="55" src="https://www.gitbook.com/cdn-cgi/image/height=55,fit=contain,dpr=1,format=auto/https%3A%2F%2F2775338190-files.gitbook.io%2F~%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FNkEGS7hzeqa35sMXQZ4X%252Flogo%252FTO5E3RjWKeaJmYYWMGWV%252Fspaces_gitbook_avatar-rectangle.png%3Falt%3Dmedia%26token%3Da34e957e-f044-4bee-abee-23946d2e9cfb" /></a>&nbsp;&nbsp;&nbsp;
<a href="https://www.linode.com/?from=bottles"><img height="48" src="https://usebottles.com/uploads/linode-brand.png" /></a>
