# Dotfiles (Fish Shell)

My Personal dotfiles

## Components

There's a few special files in the hierarchy.

- **Brewfile**: This is a list of applications for [Homebrew Cask](http://caskroom.io) to install: Applications like Firefox and 1Password.
- **topic/\*.symlink**: Any file ending in `*.symlink` gets symlinked into
  your `$HOME`. This is so you can keep all of those versioned in your dotfiles
  but still keep those autoloaded files in your home directory. These get
  symlinked in when you run `bootstrap.sh`.

## Installation

Run:

```sh
git clone git@github.com:Plastix/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
./bootstrap.sh
```

This will symlink the appropriate files in `.dotfiles` to your home directory.
Everything is configured and tweaked within `~/.dotfiles`.

## Attributions
- @holman: Dotfiles base install scripts
- @nicksp: Some shell aliases
- @mathiasbynens: Custom MacOS script
