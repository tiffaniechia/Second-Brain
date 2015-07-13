##DevOps

### Talks:
Power-packed ChefConf keynote by Jez Humble https://www.youtube.com/watch?v=L1w2_AY82WY
- Main ideas of how to structure a team for continuous delivery
- Quick touch on State of DevOps 2014
- Trunk based development/ continuous delivery examples (Google, Amazon)
- Example on G. Linden from Amazon on the Amazon shopping cart

### Best practices for bash scripts:
- http://kvz.io/blog/2013/11/21/bash-best-practices/
- http://redsymbol.net/articles/unofficial-bash-strict-mode/

### Configuration Management:
- Great comprehensive article on Salstack Vs Ansible: http://jensrantil.github.io/salt-vs-ansible.html


####Keeping an eye out for:
- Google's new Build tool: Bazel.io

### Elastic Search:
- 10 metrics for elasticsearch:  http://blog.sematext.com/2015/05/05/top-10-elasticsearch-metrics-to-watch/

### Techniques:
- Canary builds:  http://www.thoughtworks.com/radar/techniques/canary-builds
- Generated infrastructure diagrams: http://www.thoughtworks.com/radar/techniques/generated-infrastructure-diagrams

###Vagrant Reading list & beginner practice flow:
- Exercise 1:
Create a vagrant file such that doing vagrant up will start a ubuntu linux vm.
Setup a vagrant provisioner (simplest is shell provisioner) to install nginx.
Run nginx on port 80 on VM.
Setup port forward from 80 to 8080 on host.
browse 8080 from host and see the index page server by nginx from VM.
destroy VM and run vagrant up again.
- Exercise 2:
Provision nginx above using Ansible.
- Exercise 3:
Run acl on vm and map acl port to host.
- Exercise 4:
Run ACL on VM with source code shared with host so that you can still edit the code in IDE in your host.


Philosophy of Vagrant
http://mitchellh.com/the-tao-of-vagrant

Using packer and vagrant together?
http://blog.codeship.com/packer-vagrant-tutorial/

Download vagrant boxes from
http://www.vagrantbox.es/

To really understand LXC,
https://www.berrange.com/posts/2011/09/27/getting-started-with-lxc-using-libvirt/
