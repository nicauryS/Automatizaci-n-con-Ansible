Vagrant.configure("2") do |config|
  (1..3).each do |i|
    config.vm.define "vm#{i}" do |node|
      node.vm.box = "ubuntu/bionic64"
      node.vm.provider "virtualbox" do |vb|
        vb.memory = "256"
        vb.cpus = 1
      end
    end
  end
end
