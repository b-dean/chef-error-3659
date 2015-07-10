Vagrant.configure(2) do |config|
  config.vm.box = "chef/centos-6.6"
  config.vm.provision :chef_solo do |chef|
    chef.cookbooks_path = 'cookbooks'
    chef.add_recipe('foo::default')
  end
end
