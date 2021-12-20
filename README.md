Playbook to check interface status based on baseline.
Uses pyats parser and pyats diff

Executing 
- ansible-playbook rint.yml -i inv.yml --skip-tags always --> will run the baseline task
- ansible-playbook rint.yml -i inv.yml --skip-tags base --> will run the current status task
