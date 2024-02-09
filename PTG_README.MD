cd repos/k3s-ansible/
 2002  history
 2003  ansible-playbook add-master-node.yml -i inventory/dragonball/hosts.ini
 2004  ssh deployer@192.168.123.202
 2005  ansible-playbook add-master-node.yml -i inventory/dragonball/hosts.ini
 2006  ansible-playbook reset.yml -i inventory/dragonball/hosts.ini
 2007  ansible-playbook add-master-node.yml -i inventory/dragonball/hosts.ini
 2008  ssh deployer@192.168.123.211
 2009  ssh-keygen -f "/home/parkerg21/.ssh/known_hosts" -R "192.168.123.211"
 2010  ssh deployer@192.168.123.211
 2011  cd ../proxmox/terraform_pve/k8s-cluster-workers-son-vegeta-00/
 2012  tg init
 2013  curl -I https://registry.terraform.io/.well-known/terraform.json
 2014  tg init
 2015  tg plan
 2016  tg apply
 2017  ssh deployer@192.168.123.211
 2018  ssh-keygen -f "/home/parkerg21/.ssh/known_hosts" -R "192.168.123.211"
 2019  ssh deployer@192.168.123.211
 2020  ansible-playbook reset.yml -i inventory/dragonball/hosts.ini
 2021  cd ../../../k3s-ansible/
 2022  ansible-playbook reset.yml -i inventory/dragonball/hosts.ini
 2023  ansible-playbook site.yml -i inventory/dragonball/hosts.ini
 2024  ansible-playbook add-worker-node.yml -i inventory/dragonball/hosts.ini
 2025  ansible-playbook site.yml -i inventory/dragonball/hosts.ini
 2026  k get nodes
 2027  k nodes
 2028  ansible-playbook add-worker-node.yml -i inventory/dragonball/hosts.ini
 2029  ansible-playbook site.yml -i inventory/dragonball/hosts.ini
 2030  history