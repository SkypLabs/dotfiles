# Dotfiles

![Travis (.com) branch](https://img.shields.io/travis/com/SkypLabs/dotfiles/master?label=master&logo=travis) ![Travis (.com) branch](https://img.shields.io/travis/com/SkypLabs/dotfiles/develop?label=develop&logo=travis)

This repository contains my dotfiles.

The different configuration files are organised into topics, one folder per topic.

## Installation

I use [Dotbot][dotbot] to automatically install my dotfiles:

1. Clone this repository with the following command:

        git clone https://github.com/SkypLabs/dotfiles.git ~/.dotfiles

2. Run `cd ~/.dotfiles && ./install`

The Vim plugin [coc.nvim][coc-nvim] needs a [Node.js][nodejs-download] runtime
environment to function as well as the [npm][npm] or [yarn][yarn] package
manager to download and install the coc extensions.

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
 [nodejs-download]: https://nodejs.org/en/download/ "Node.js download page"
 [npm]: https://www.npmjs.com/get-npm "npm download page"
 [yarn]: https://yarnpkg.com/ "Yarn official website"
