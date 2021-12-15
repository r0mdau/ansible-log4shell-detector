ansible-log4shell-detector-playbook
===================================

It is an example playbook to run [r0mdau/log4shell-detector](https://github.com/r0mdau/ansible-role-log4shell-detector) ansible role.
You will find more informations in the role README.

## Quick start

    git clone https://github.com/r0mdau/ansible-log4shell-detector.git
    cd ansible-log4shell-detector
    ansible-galaxy install r0mdau.log4shell_detector

Edit hosts/inventory or use any other ansible inventory.

Finally launch the playbook

    ansible-playbook -i hosts/inventory playbook.yml

Example to read output file with jq

    cat log4shell_detector_192.168.56.11.log | jq .stdout_lines


## Informations

Python tool [log4shell-detector](https://github.com/Neo23x0/log4shell-detector) by Neo23x0.
Secon scan Go tool [local-log4j-vuln-scanner](https://github.com/hillu/local-log4j-vuln-scanner) by hillu.
