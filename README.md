This repo allows easy deploy of all custom dotfiles to any *nix system.
A quick way to get all your configs on a new system.


To deploy and use this repo, run the following commands on any *nix system:

mkdir ~/dotfiles_repo
cd ~/dotfiles_repo
git clone git@github.com:carbide20/dotfiles.git .
chmod +x deploy
./deploy

You may have to close and open the terminal or tmux window for dotfiles to work.
Top test, you can run:

shebang

and it should output:

#!/usr/bin/env bash

That means it's working.
