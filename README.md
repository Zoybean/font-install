font-install
============

Install TTF Fonts on Linux.

The idea started from here http://jorrel.blogspot.it/2007/11/monaco-on-ubuntu.html.
The original goal of the repo was to provide a script to download and install the `Monaco` font on ubuntu rather than provide the font itself. Now it exists simply as a set of scripts to easily install new fonts on Linux.

All the scripts accept as a parameter a raw `url` that points to the font.

A list of open-source fonts can be found right here on GitHub:
* https://github.com/showcases/fonts

---

**Disclaimer**: Users should know the font license before downloading and installing it. This repo provides the scripts to download and install fonts on your linux distro. All the scripts are provided as-is and have the public domain license; so you can copy, modify, use and so on without restrictions. 
**Do not use fonts without permission.**

---

## HOW TO

* Clone the repository
* launch the script and replace `[url]` with the url of the font, e.g. 

``` bash
./install-font-ubuntu.sh https://github.com/chrissimpkins/codeface/raw/master/fonts/terminus/Terminus.ttf
```


---
#### Install Font on Ubuntu

```bash
./install-font-ubuntu.sh [url]
```

#### Install Font on CentOS

```bash
./install-font-centos.sh [url]
```

#### Install Font on Gentoo

```bash
./install-font-gentoo.sh [url]
```

