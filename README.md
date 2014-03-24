OpenVPN-Ansible
===============

Ansible playbook for OpenVPN.

Target linux dist is CentOS 6 x64

Add ca.crt, server.crt and server.key, client key pair and dh.pem on the keys directory.

Set server ip address and domain name.

*ansible-playbook site.yml -i hosts*
