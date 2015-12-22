# ndenv-sudo

ndenv-sudo is a plugin for ndenv that allows you to run ndenv-provided
node from within a `sudo` session.

## Implementation

ndenv-sudo is a clone of rbenv-sudo.

https://github.com/dcarley/rbenv-sudo

## Installation

1. Setup ndenv
1. Make sure you have a plugins directory:

        mkdir ~/.ndenv/plugins

1. Clone `ndenv-sudo` into the plugins directory:

        git clone git://github.com/dcarley/rbenv-sudo.git ~/.rbenv/plugins/rbenv-sudo

## Usage

Prefix your use of sudo with the `ndenv` command:

    $ ndenv sudo chef-solo --version
    Chef: 0.10.8
    $ ndenv sudo node --version
    v5.3.0

## License

This code is provided under the MIT license.
