# Ansible hostvars resolution issue reproduction

Ansible hostvars reference in group vars resolves incorrectly. To reproduce, run:

```shell
ansible-playbook -i inventory test.yml
```

Reference / correct outputs are prefixed with `REF` while incorrect with `BUG`.
