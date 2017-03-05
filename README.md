# DevOps box:
* A vagrant project with an ubuntu box with the tools needed to do DevOps

# Tools included:
* Ansible
* AWS CLI
* Docker-CE
* Terraform

# Differences from Edward's version:
* Added a sed command to replace default apt repository location
 * It currently uses Singapore's repository, but change it as you wish.

* Changed installation of docker.io to docker-ce
 * As per official instructions at the following link: https://docs.docker.com/engine/installation/linux/ubuntu/
