Vagrant::Config.run do |config|
    config.vm.box = "quantal"
    #config.vm.box = "lucid32"

    config.vm.provision :chef_solo do |chef|
      #chef.cookbooks_path = ["cookbooks/ci_environment"]
      chef.cookbooks_path = ["cookbooks"]
      #chef.add_recipe "build-essential"
      chef.add_recipe "haskell"
    end
end
