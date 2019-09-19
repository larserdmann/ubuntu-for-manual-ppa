# ubuntu-for-manual-ppa

Build a docker image in which you can add ppa's manually by providing the ppa and key.

Copy ppa to `/etc/apt/sources.list.d/[some ppa]` and 
provide key by `apt-key adv --keyserver keyserver.ubuntu.com --recv-keys [somekey]`.

After `apt-get update` ubuntu is ready to use the ppa.
