# OS X Developer Setup
Script to setup a Ruby development environment for your OS X machine.
Tested on Catalina.

## Install
* Install the Command Line Tools for Xcode

  ```
  xcode-select --install
  ```
* Open a new terminal session and run this one-liner:

  ```
  zsh < <(curl -s https://raw.github.com/janogonzalez/osx-developer-setup/master/install)
  ```

The script will add a few lines to your `.zshrc`.

## What it sets up
### SSH keys
Copies your public SSH key to the clipboard so you can paste it on your GitHub
account configuration. If you don't have a SSH Key it will create one for you.

### [Homebrew](http://mxcl.github.com/homebrew/)
A great package manager, it's used to install the rest of the software.

### [Ag](https://geoff.greer.fm/ag/)
A tool like grep, optimized for searching in source code files.

### [Neovim](https://neovim.io/)
A great text editor.

### [Tmux](http://tmux.sourceforge.net/)
A terminal multiplexer, allows to run multiple terminals from a single screen.

### [Ctags](http://ctags.sourceforge.net/)
A tool to index language objects like classes, functions, etc. to easily
locate them by text editors and other tools.

### [chruby](https://github.com/postmodern/chruby)
A tool for managing different Ruby versions.

### [ruby-build](https://github.com/sstephenson/ruby-build)
A tool to compile different Ruby versions.

### [Ruby](http://www.ruby-lang.org/)
The latest stable Ruby version.

It should take about 30 minutes for everything to install, depending on your
machine.

## Recommended
This stuff doesn't come in the script.

### [Prezto](https://github.com/sorin-ionescu/prezto)
A great configuration framework for zsh.

### [Base16](https://github.com/vbwx/base16-terminal-app)
A color theme for Terminal.app

### [AppCleaner](http://www.freemacsoft.net/appcleaner/)
A utility to uninstall software.

### [Onyx](http://www.titanium.free.fr/download.php)
A great tool for system maintenance and personalization.
