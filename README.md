Vagrant Development Environment
===============================

Prerequisites:

  * [Git](http://git-scm.com/downloads)
  * [Packer](http://www.packer.io/downloads.html)
  * [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
  * [Vagrant](https://www.vagrantup.com/downloads.html)

Instructions:

```sh
git clone https://github.com/a1russell/vagrant-devenv.git vagrant-devenv
cd vagrant-devenv
packer build wheezy64
vagrant up
```
