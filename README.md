This [rbenv](http://rbenv.org/) plugin allows easier switching between Ruby versions without having to keep patchlevels in mind.

Pro tip: Alias `rbenv` to `rvm` to ease transition. The `--global` option is aliased to `--default` exactly for that purpose.

## Usage examples

Switch current shell to latest stable JRuby:

    rbenv use jruby

Switch to whatever would be default (global or local):

    rbenv use default

Make latest stable 1.9.3 global default and switch to using it:

    rbenv use 1.9.3 --global

Make whatever the current Ruby is the global default:

    rbenv use current --global

Make whatever the current Ruby is the local default:

    rbenv use current --local

Make whatever the local Ruby is the global default:

    rbenv use local --global

Use 2.0 development version:

    rbenv use 2.0

Use rbx development version:

    rbenv use rbx

## Installation

Run these commands:

    mkdir -p $RBENV_ROOT/plugins
    git clone https://github.com/rkh/rbenv-whatis.git $RBENV_ROOT/plugins/rbenv-whatis
    git clone https://github.com/rkh/rbenv-use.git $RBENV_ROOT/plugins/rbenv-use

Skip the first `git clone` if you already installed [rbenv-whatis](https://github.com/rkh/rbenv-whatis).