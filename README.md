# Dotfiles

This repository contains my dotfiles.

The different configuration files are organised into topics, one folder per topic.

## Installation

I use [Dotbot][dotbot] to automatically install my dotfiles:

1. Clone this repository with the following command:

        git clone https://github.com/SkypLabs/dotfiles.git ~/.dotfiles

2. Run `cd ~/.dotfiles && ./install`

## Troubleshooting

### Vim

At the first launch, you will likely see the following message showing up:

    Warning: Cannot find word list "fr.latin1.spl" or "fr.ascii.spl"

To install the missing word lists, use the `:set spell` command. You will be prompted to install them.

## License

[MIT][mit-license]

 [dotbot]: https://github.com/anishathalye/dotbot "Dotbot project on GitHub"
 [mit-license]: https://opensource.org/licenses/MIT "MIT license"
