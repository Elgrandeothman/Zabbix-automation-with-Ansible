# Zabbix-automation-with-Ansible

## Introduction
This repository contains ansible playbooks for the installation and configuration of : { zabbix-server with mariadb database and frontend }, { zabbix-agent },
in AWS cloud environnement using ec2-instances running amazon-linux os .

## Structure
We gonna need 4 ec2-instances :
- Control-node
- Zabbix-server-node
- worker-node1
- worker-node2

### Control-node 
The node where we install ansible so we can run our playbooks
### Zabbix-server-node
The node where we gonna have our zabbix-server running with database and frontend 
### worker-node1/node2
The nodes that we are going to monitor and where we gonna install zabbix-agent 


