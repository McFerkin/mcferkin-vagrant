Vagrant::Config.run do |config|
    config.vm.box = "quantalServer64"

    config.vm.provision :chef_solo do |chef|
      chef.cookbooks_path = ["cookbooks"]
      chef.add_recipe "haskell"
    end
end
