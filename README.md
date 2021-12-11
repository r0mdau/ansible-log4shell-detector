ansible-log4shell-detector-playbook
===================================

It is an example playbook to run [r0mdau/log4shell-detector](https://github.com/r0mdau/ansible-role-log4shell-detector) ansible role.
You will find more informations in the role README.

## Quick start

    git clone https://github.com/r0mdau/ansible-log4shell-detector-playbook.git
    cd ansible-log4shell-detector-playbook
    ansible-galaxy install r0mdau.log4shell_detector

Edit hosts/inventory or use any other ansible inventory.

    ansible-playbook -i hosts/inventory playbook.yml

## Informations

Python script [log4shell-detector](https://github.com/Neo23x0/log4shell-detector) by Neo23x0.
