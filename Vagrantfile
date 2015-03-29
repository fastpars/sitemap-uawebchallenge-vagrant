# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
Vagrant.require_version ">= 1.6"

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
	ENV['VAGRANT_DEFAULT_PROVIDER'] = 'docker'

  config.vm.provider "docker" do |d|
    d.build_dir = "."
    d.name = "fastpars-sitemap"
    d.ports = ["8888:8888"]
  end
end
