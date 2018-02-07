Vagrant.configure(2) do |config|
    config.ssh.insert_key = false
    config.vm.box = "bento/centos-7.1"
    config.vm.hostname = "ansible.dev"
    config.vm.network "private_network",ip:"192.168.34.21"
    config.vm.synced_folder ".", "/vagrant", mount_options: ["dmode=777", "fmode=666"]
end
