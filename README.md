![bash_unit CI](https://github.com/pforret/font/workflows/bash_unit%20CI/badge.svg)
![Shellcheck CI](https://github.com/pforret/font/workflows/Shellcheck%20CI/badge.svg)
![GH Language](https://img.shields.io/github/languages/top/pforret/font)
![GH stars](https://img.shields.io/github/stars/pforret/font)
![GH tag](https://img.shields.io/github/v/tag/pforret/font)
![GH License](https://img.shields.io/github/license/pforret/font)
[![basher install](https://img.shields.io/badge/basher-install-white?logo=gnu-bash&style=flat)](https://basher.gitparade.com/package/)

# font

manage installed fonts for Linux and MacOS

## 🚀 Installation

with [basher](https://github.com/basherpm/basher)

	$ basher install pforret/font

or with `git`

	$ git clone https://github.com/pforret/font.git
	$ cd font

## 🔥 Usage
```
Program: font 0.0.2 by peter@forret.com
Updated: Feb 15 23:47:05 2021
Description: manage installed fonts for Linux and MacOS
Usage: font [-h] [-q] [-v] [-f] [-l <log_dir>] [-t <tmp_dir>] <action> <input?>
Flags, options and parameters:
-h|--help        : [flag] show usage [default: off]
-q|--quiet       : [flag] no output [default: off]
-v|--verbose     : [flag] output more [default: off]
-f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
-l|--log_dir <?> : [option] folder for log files   [default: /Users/pforret/log/font]
-t|--tmp_dir <?> : [option] folder for temp files  [default: .tmp]
<action>         : [parameter] action to perform: install/uninstall/search/list
<input>          : [parameter] input font name  (optional)
```

## 📝 Acknowledgements

* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2021 Peter Forret
