# Ansible-with-Tomcat-Jankins
Requires two virtual machines on Centos 7
Set ip-addresses of web-server and app-server
Copy ssh-key on VM's
Add server's addresses in your /etc/hosts
192.168.100.105  app-server.vm app-server
192.168.100.104  web-server.vm web-server
Then Run
ansible-playbook Main.yml
