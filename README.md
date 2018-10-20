# Provision

# How to use

Create your `hosts` file using `hosts.dist`
Create your `project.yml` file using `project.yml.dist`

```bash
cd centos
ansible-galaxy install -r requirements.yml
ansible-playbook playbook.yml --extra-vars="target=project" --user root

cd /etc/nginx
sudo mkdir ssl
sudo openssl dhparam -out /etc/nginx/ssl/dhparam.pem 2048
```

# Features

- Php 7.1
- Nginx 1.15
- MariaDB 10.1
- Let's encrypt SSL
