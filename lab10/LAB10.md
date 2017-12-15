### Lab #10 Multi-node Vagrant environment

**Task:** Create Vagrant environment that brings up 2 machines with direct names visilibity.

1. Single Vagrantfile
2. OS: centos 6.9
3. subnet: 10.1.1.0/24
4. Use Static IP addresses
5. Names: node1.local, node2.local
6. Tip: configure /etc/hosts records
7. Tip:
```ruby
config.vm.define "node1" do |node1|
  ...
  node1.vm.network :private_network, ip: '10.1.1.10'
```
