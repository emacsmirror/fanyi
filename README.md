<div align="center">

[![build](https://github.com/condy0919/fanyi.el/actions/workflows/build.yml/badge.svg)](https://github.com/condy0919/fanyi.el/actions/workflows/build.yml)
[![License](http://img.shields.io/:license-gpl3-blue.svg)](LICENSE)
![Supports Emacs 27.1-28.x](https://img.shields.io/badge/Supports-Emacs_27.1_--_28.x-blueviolet.svg?style=flat-square&logo=GNU%20Emacs&logoColor=white)
[![MELPA](https://melpa.org/packages/fanyi-badge.svg)](https://melpa.org/#/fanyi)

</div>

# fanyi.el

`fanyi.el` is a simple yet powerful multi-dictionaries interface for Emacs, includes:

- [`海词`](https://dict.cn/)
- [`etymonline`](https://www.etymonline.com/)
- [`American Heritage dictionary`](https://ahdictionary.com/)

## Installation

Install `fanyi.el` from [MELPA](https://melpa.org) with:

```
M-x package-install RET fanyi RET
```

If you're a American Heritage Dictionary user, make sure `Minion New` font is
installed. Otherwise the pronunciation may be displayed in tofu, or an
`all-the-icons` icon if you have `all-the-icons` installed.

``` shell
# family: Minion New Bold
# https://ahdictionary.com/application/resources/fonts/MinionNew-Bold.ttf
#
# family: Minion New Italic
# https://ahdictionary.com/application/resources/fonts/MinionNew-Italic.ttf
curl https://ahdictionary.com/application/resources/fonts/MININ___.TTF -o Minion.ttf

# linux
mv Minion.ttf ~/.local/share/fonts/

# macOS
mv Minion.ttf ~/Library/Fonts/
```

## Usage

`fanyi-dwim`, that's all!

# Screenshots

![海词](https://user-images.githubusercontent.com/4024656/128582690-2af2bb4a-46aa-4241-bdc0-6a5bb5e2db38.png)
![分布](https://user-images.githubusercontent.com/4024656/128582703-3e62cd17-a778-4982-9872-98e8697e333e.png)
![Etymon](https://user-images.githubusercontent.com/4024656/128583142-dfd26d67-45c5-482a-9268-d7482dbe65f3.png)

## Similar projects

- [youdao-dictionary](https://github.com/xuchunyang/youdao-dictionary.el)
- [bing-dict](https://github.com/cute-jumper/bing-dict.el)
