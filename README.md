# ansible-unifi

Note: You need at least Ansible 2.9.

## Ansible

Setup ansible locally.

### Install Ansible

See documentation [here](docs/install-ansible.md)

## Proxmox requirements for container

- check all boxes in option > features
- copy your ssh-key on the container 

## Edit hosts

vim hosts

## Run playbook

ansible-playbook playbook.yaml

## Go on URL for complete setup

https://<YOUR_HOST_IP>:8443/


 Voici ci-dessous les caractéristiques de l'arborescence d'un rôle :

    tasks: contient la liste principale des tâches à exécuter par le rôle.
    handlers: contient les handlers, qui peuvent être utilisés par ce rôle ou même en dehors de ce rôle.
    defaults: variables par défaut pour le rôle.
    vars: d'autres variables pour le rôle.
    files: contient des fichiers qui peuvent être déployés via ce rôle.
    templates: contient des modèles (jinja2) qui peuvent être déployés via ce rôle.
    meta: définit certaines métadonnées pour ce rôle.
    README.md: inclut une description générale du fonctionnement de votre rôle.
    test: contient notre playbook (on peut cependant déposer notre playbook à la racine du projet ou dans un dossier sous un nom différent).
