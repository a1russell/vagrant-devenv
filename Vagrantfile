# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant::Config.run do |config|
  config.vm.box = "vagrant-devenv"
  config.vm.box_url = "vagrant-devenv.box"

  config.vm.boot_mode = :gui

  config.vm.provision :puppet do |puppet|
    puppet.manifests_path = "manifests"
    puppet.module_path = ["modules-contrib","modules-custom"]
    puppet.manifest_file = "base.pp"
    puppet.hiera_config_path = "hiera.yaml"
  end
end
