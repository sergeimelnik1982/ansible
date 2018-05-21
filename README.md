# ansible
ansible role for l2tp+ipsec PSK on Digital Ocean Ubuntu 16.04 LTS

playbook example:

- hosts: vpn
  roles:
    - role: l2tp-ipsec
