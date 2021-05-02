![bash_unit CI](https://github.com/pforret/font/workflows/bash_unit%20CI/badge.svg)
![Shellcheck CI](https://github.com/pforret/font/workflows/Shellcheck%20CI/badge.svg)
![GH Language](https://img.shields.io/github/languages/top/pforret/font)
![GH stars](https://img.shields.io/github/stars/pforret/font)
![GH tag](https://img.shields.io/github/v/tag/pforret/font)
![GH License](https://img.shields.io/github/license/pforret/font)
[![basher install](https://img.shields.io/badge/basher-install-white?logo=gnu-bash&style=flat)](https://basher.gitparade.com/package/)

# font

manage installed fonts for Linux and MacOS

## 🔥 Usage
```bash
Program: font 0.1.2 by peter@forret.com
Updated: May  2 23:33:51 2021
Description: manage installed fonts for Linux and MacOS
Usage: font [-h] [-q] [-v] [-f] [-d] [-l <log_dir>] [-t <tmp_dir>] <action> <input?>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -q|--quiet       : [flag] no output [default: off]
    -v|--verbose     : [flag] output more [default: off]
    -f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
    -d|--detail      : [flag] search for individual fonts, not just families [default: off]
    -l|--log_dir <?> : [option] folder for log files   [default: /Users/pforret/log/font]
    -t|--tmp_dir <?> : [option] folder for temp files  [default: /Users/pforret/.tmp]
    <action>         : [parameter] action to perform: install/uninstall/search/list/info
    <input>          : [parameter] input font name  (optional)

### TIPS & EXAMPLES
* use font install to install a font
  font install Bitter-SemiBoldItalic
* use font uninstall to uninstall a font
  font uninstall Faustina-BoldItalic
* use font search to look for a downloadable font
  font search script
* use font info to get more info on a font
  font info OleoScriptSwashCaps
* use font list to show all locally installed fonts
  font list
* use font check to check if this script is ready to execute and what values the options/flags are
  font check
* use font env to generate an example .env file
  font env > .env
* use font update to update to the latest version
  font check
```

## 🚀 Installation

with [basher](https://www.basher.it)

	$ basher install pforret/font

or with `git`

	$ git clone https://github.com/pforret/font.git
	$ cd font

## 📝 Acknowledgements

* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2021 Peter Forret
