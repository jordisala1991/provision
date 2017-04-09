# Provision

*This only works for CentOS 7*

# How to use

Create your `hosts` file using `hosts.dist`
Create your `secret.yml` file using `secret.yml.dist`

```bash
ansible-galaxy install -r ansible/requirements.yml
ansible-playbook ansible/playbook.yml --user root
```

# Features

- Php 7.1
- Apache 2.4
- MariaDB 10.1
- Let's encrypt SSL

# To Do

- Add Debian support
- Add nginx support
