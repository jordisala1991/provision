# Provision

# How to use

Create your `hosts` file using `hosts.dist`
Create your `project.yml` file using `project.yml.dist`

```bash
cd centos
ansible-galaxy install -r requirements.yml
ansible-playbook playbook.yml --user root
```

# Features

- Php 7.1
- Nginx 1.15
- MariaDB 10.1
- Let's encrypt SSL
