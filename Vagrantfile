# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

require 'yaml'

current_dir    = File.dirname(File.expand_path(__FILE__))
configs        = YAML.load_file("#{current_dir}/config.yaml")
vagrant_config = configs['configs'][configs['configs']['use']]

if vagrant_config['proxy']['enabled']
  ENV['http_proxy'] = vagrant_config['proxy']['http']
  ENV['https_proxy'] = vagrant_config['proxy']['https']
  ENV['ftp_proxy'] = vagrant_config['proxy']['ftp']
  ENV['no_proxy'] = vagrant_config['proxy']['no_proxy']
end

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  unless Vagrant.has_plugin?("vagrant-vbguest")
    raise "vagrant-vbguest plugin not installed! Run vagrant plugin install vagrant-vbguest."
  end

  unless Vagrant.has_plugin?("vagrant-proxyconf")
    raise "vagrant-proxyconf plugin not installed! Run vagrant plugin install vagrant-proxyconf."
  end

  ## Configure proxy with vagrant-proxyconf
  config.proxy.enabled = vagrant_config['proxy']['enabled']
  config.proxy.http = vagrant_config['proxy']['http']
  config.proxy.https = vagrant_config['proxy']['https']
  config.proxy.ftp = vagrant_config['proxy']['ftp']
  config.proxy.no_proxy = vagrant_config['proxy']['no_proxy']

  ## Configure vagrant
  config.vm.box = "ubuntu/wily64"
  config.vm.hostname = vagrant_config['vm']['hostname']
  config.vm.network:forwarded_port, guest: 4000, host: vagrant_config['vm']['port']
  config.vm.network:private_network, ip: vagrant_config['vm']['private_ip']
  config.ssh.forward_agent = true

  config.vm.provider "virtualbox" do |v|
    v.memory = vagrant_config['vm']['memory']
    v.cpus = vagrant_config['vm']['cpu']
  end

  config.vm.provider "vmware_fusion" do |v|
    v.vmx["memsize"] = "#{vagrant_config['vm']['memory']}"
    v.vmx["numvcpus"] = "#{vagrant_config['vm']['cpu']}"
  end

  config.vm.provision :shell,
    :inline => "sudo apt-get update &&
                sudo apt-get -y install build-essential git ruby2.2 ruby2.2-dev nodejs &&
                sudo ln -s -f /usr/bin/gem2.2 /usr/bin/gem &&
                sudo gem install github-pages --no-ri --no-rdoc"

end
