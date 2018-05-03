# wslu - A collection of utilities for WSL

[![Wiki](https://img.shields.io/badge/Wiki-wslu-blue.svg)](https://github.com/patrick330602/wslu/wiki) [![GitHub license](https://img.shields.io/github/license/patrick330602/wslu.svg)](https://github.com/patrick330602/wslu/blob/master/LICENSE) [![GitHub (pre-)release](https://img.shields.io/github/release/patrick330602/wslu/all.svg)](https://github.com/patrick330602/wslu)

This is a collection of utilities for Windows 10 Linux Subsystem, such as enabling sound in WSL or creating your favorite linux GUI application shortcuts on Windows 10 Desktop. Requires Windows 10 Creators Update.

**Currently supported Distro:**
- Ubuntu (Store)
- OpenSUSE
- SUSE Linux Enterprise Server(SLES)
- Debian GNU/Linux
- Kali Linux

## Feature

**wslusc**
This is a WSL shortcut creator to create shortcut on your Windows 10 Desktop.

**wslsys**
This is a WSL system information printer to print out some basic system information.

**wslpkg**
This is WSL Package Installer, which is a minimal package manager for installing special packages. Also, it provide some simple commands to install apps from third-party repositories.

**wslfetch**
This is a WSL Screenshoot Information Tool to print information in a elegant way.

**wslupath**
This is a WSL Windows path Converter that can convert Windows path to other styles of path.

**wsluconf**

This is a tool to help set up wslu.

## Installation

<del>TO install, just run the following command in the bash prompt:</del>
<del>`curl -o- https://raw.githubusercontent.com/patrick330602/wslu/master/extras/scripts/install.sh | bash`</del>

Latest version is not suggested to be installed now. the installation is being modified. please use the release version of installation script:

```
git clone --branch v1.2 https://github.com/patrick330602/wslu.git ~/.wslu
cd ~/.wslu
./configure -i
```

## License

<pre>
This is free software; you can redistribute it and/or modify
it under the terms of the GNU GPL version 3 or (at your option) any later version.
There is NO warranty; not even MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
</pre>
