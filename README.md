SAMI BEN EL FAHSI
B3B


```
git clone https://github.com/sami247/TP_Ansible.git

```

ajouter les ip dans  `inventory.ini` 

```
172.16.0.100
172.16.0.101
172.16.0.102

[web]
devops01 ansible_host=172.16.0.100
devops02 ansible_host=172.16.0.101

[db]
devops03 ansible_host=172.16.0.102


```
Démarrer le playbooks
```
ansible-playbook playbooks/deploy_projet.yml
```

