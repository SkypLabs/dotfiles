# Dotfiles

[![Test](https://github.com/SkypLabs/dotfiles/actions/workflows/test.yml/badge.svg)](https://github.com/SkypLabs/dotfiles/actions/workflows/test.yml)

This repository contains my dotfiles.

The different configuration files are organised into topics, one folder per topic.

## Installation

I use [Dotbot][dotbot] to automatically install my dotfiles:

1. Clone this repository with the following command:

        git clone https://github.com/SkypLabs/dotfiles.git ~/.dotfiles

2. Run `cd ~/.dotfiles && ./install`

### coc.nvim

The Vim plugin [coc.nvim][coc-nvim] needs a [Node.js][nodejs-download] runtime
environment to function as well as the [npm][npm] or [yarn][yarn] package
manager to download and install the coc extensions.

### Starship

[Starship][starship] requires to install and enable a [Nerd Font][nerd-font].

For example, to install the **FiraCode Nerd Font**:

```raw
wget https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/FiraCode.zip
unzip -d ~/.local/share/fonts/ ~/Downloads/FiraCode.zip
fc-cache -fv ~/.local/share/fonts
```

Then, it needs to be set as your terminal font.

## Troubleshooting

### Vim

At the first launch, you will likely see the following message showing up:

    Warning: Cannot find word list "fr.latin1.spl" or "fr.ascii.spl"

To install the missing word lists, use the `:set spell` command. You will be
prompted to install them.

## License

[MIT][mit-license]

 [coc-nvim]: https://github.com/neoclide/coc.nvim "coc.nvim Vim plugin"
 [dotbot]: https://github.com/anishathalye/dotbot "Dotbot project on GitHub"
 [mit-license]: https://opensource.org/licenses/MIT "MIT license"
 [nerd-font]: https://www.nerdfonts.com/ "Nerd Font official website"
 [nodejs-download]: https://nodejs.org/en/download/ "Node.js download page"
 [npm]: https://www.npmjs.com/get-npm "npm download page"
 [starship]: https://starship.rs/ "Starship official website"
 [yarn]: https://yarnpkg.com/ "Yarn official website"
