Vagrant.configure("2") do |config|
  config.vm.define "example" do |example|
    example.vm.box = "centos/7"
    example.vm.network "forwarded_port", guest: 8000, host: 8000
    example.vm.network :private_network, ip: "11.0.0.7"
  end
end
