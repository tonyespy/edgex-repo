This repository hosts an experimental repo XML manifest for
EdgeX Foundry's code hosted on git hub.

This manifest can be used to initialize repo like this:

$ mkdir $HOME/edgex-dev
$ cd $HOME/edgex-dev
$ repo init -u git@github.com:tonyespy/edgex-repo.git

Then the code can all be retrived by running this command:

$ repo sync

To install repo, please refer to:

https://source.android.com/source/downloading#installing-repo
