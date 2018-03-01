## vagrant-ssh

Copy current dir to `$VAGRANT_HOST` and run provided Vagrant command remotely via ssh tunnel.
Vagrant should be installed at `$VAGRANT_HOST`.


#### Example
      > ./vagrant-ssh -s user@alpha up

      > VAGRANT_VAGRANTFILE=./Vagrantfile-remote VAGRANT_HOST=user@alpha ./vagrant-ssh ssh
