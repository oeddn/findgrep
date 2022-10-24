# Installation
- choose a directory for installation, e.g. `~/.scripts` (will be referred to as `<inst_dir>` below)
- clone github repository, for example to the installation directory:

    git clone git@github.com:oeddn/scripts.git <inst_dir>

- add the installation directory to PATH; there are several possibilities to do this, e.g. modification of `~/.profile`, which affects the current user only (note that you might want to change the `~/` inside your `<inst_dir>` to `$HOME/`):

    echo 'PATH="<inst_dir>:$PATH"' >> ~/.profile

