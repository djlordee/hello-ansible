# hello-ansible
Ce projet permettra de démontrer l'utilisation de l'outil Ansible pour automatiser les tâches de mise-à-jour d'ordinateurs Raspberry-PI

Les fichiers:

- pi-update.yml: Fichier qui est le Playbook Ansible pour exécuter la mise-à-jour des paquets sur les ordinateurs Raspberry-PI
- hosts: Liste des ordinateurs sur lesquels le Playbook Ansible s'exécutera

Pour exécuter cet exemple, il faut:

- Modifier le fichier hosts en y inscrivant l'adresse IP de(s) ordinateur(s) Raspberry-PI où sera exécuté la mise-à-jour
- Lancer la commande suivante: ansible-playbook pi-update.yml

