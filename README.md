# OS X Developer Setup
Script to setup a Ruby development environment for your OS X machine.
Tested on Mountain Lion. 

## Install
* Install the [Command Line Tools for Xcode](Command Line Tools for Xcode).
* Change your default shell to zsh:

  ```
  chsh -s /bin/zsh
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

### [Ack](http://betterthangrep.com/)
A tool like grep, optimized for searching in source code files.

### [MacVim](http://code.google.com/p/macvim/)
The best text editor ;).

### [Tmux](http://tmux.sourceforge.net/)
A terminal multiplexer, allows to run multiple terminals from a single screen.

### [Ctags](http://ctags.sourceforge.net/)
A tool to index language objects like classes, functions, etc. to easily
locate them by text editors and other tools.

### [GraphicsMagick](http://www.graphicsmagick.org/)
A tool to process images.

### [MySQL](http://www.mysql.com/)
An open source relational database.

### [PostgreSQL](http://www.postgresql.org/)
Another open source relational database.

### [Redis](http://redis.io/)
An open source key-value store.

### [chruby](https://github.com/postmodern/chruby)
A tool for managing different Ruby versions.

### [ruby-build](https://github.com/sstephenson/ruby-build)
A tool to compile different Ruby versions.

### [Ruby 2.0.0](http://www.ruby-lang.org/)
The latest stable Ruby version.

### [Bundler](http://gembundler.com/)
A gem to manage Ruby application dependencies.

It should take about 30 minutes for everything to install, depending on your
machine.

## Recommended
This stuff doesn't come in the script.

### [Prezto](https://github.com/sorin-ionescu/prezto)
A great configuration framework for zsh.

### [iTerm2](http://www.iterm2.com/)
A terminal emulator for OS X.

### [Solarized](http://ethanschoonover.com/solarized)
A color theme for your terminal, editors and IDEs.

### [Alfred](http://www.alfredapp.com/)
A great application launcher (and so much more).

### [AppCleaner](http://www.freemacsoft.net/appcleaner/)
A utility to uninstall software.

### [The Unarchiver](http://wakaba.c3.cx/s/apps/unarchiver.html)
A tool to unpack archives.

### [Onyx](http://www.titanium.free.fr/download.php)
A great tool for system maintenance and personalization.

### [Gitx](http://gitx.frim.nl/)
Sometimes you want a graphical history viewer...
