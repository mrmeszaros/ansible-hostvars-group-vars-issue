# Ansible hostvars resolution bug reproduction

Ansible hostvars reference in group vars resolves incorrectly. To reproduce, run:

```shell
ansible-playbook -i inventory test.yml
```
