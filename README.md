# Ansible-with-Tomcat-Jankins

# Set hosts file

## Requires two virtual machines on Centos 7

http://mirrors.datahouse.ru/centos/7.9.2009/isos/x86_64/CentOS-7-x86_64-DVD-2009.iso

## Set ip-addresses of web-server and app-server

# Copy ssh-key on VM's

## Add server's addresses in your /etc/hosts 
```
10.69.0.79   app-server
10.69.0.82   web-server
```
## Then Run
```
ansible-playbook Main.yml
```

Jenkins will aviable in http://web-server/jenkins
