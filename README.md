#### dcos-vagrant | Deploy Mesosphere DCOS Master Instance with Vagrant

##### 1. You will need vagrant installed beforehand

  - Spinning up DCOS Master

```bash
$ vagrant up

http://172.17.8.101  # may take a 10 - 15 minutes for services to come up.
```

##### 2. Spin up a slave instance that connects to master

  - Spin up a slave instance

```bash
$ git clone https://github.com/brycekottke/dcos-slave-vagrant.git
$ cd dcos-slave-vagrant
$ vagrant up
```
##### 3. Things to do / Diagnose

  - Figure out why dcos-cli will not install packages.
  - dcos-cli throws errors when running 'dcos package install jenkins'
