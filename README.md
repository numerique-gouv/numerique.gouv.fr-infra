# numerique.gouv.fr-infra

## Le fichier host

Ansible fonctionne à partir d'un système [d'inventaire](https://docs.ansible.com/ansible/latest/user_guide/intro_inventory.html) 
Ce fichier peut être ajouté à la racine pour selectionner les serveurs à configurer.

## Déploiment de la configuration

    ansible-playbook ./ansible/install-server.yml -i ./host
    
## Syncronisation du serveur

    ansible-playbook ./ansible/syncronise-server.yml -i ./host
