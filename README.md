# Gitlab Ansible Roles

Installs Gitlab on RedHat/CentOS linux system.

Gitlab's default administrator account details are below
To change these credentials or version, change it on group_vars

    gitlab_root_usr: 'root'
    gitlab_root_psw: 'password'

## Requirements

To Do.

## Tree Structure

To Do.

## Role Variables

To Do.

## License

MIT

## Runing

```
git clone https://github.com/brpedromaia/gitlab-ansible-roles.git
cd gitlab-ansible-roles
sudo ansible-playbook --connection=local playbooks/setup.yml -t install
```

## References
- [Ansible Docs](https://docs.ansible.com/)
- [Jinja Template](https://jinja.palletsprojects.com/en/2.11.x/)
- [Gitlab Docs](https://docs.gitlab.com/)