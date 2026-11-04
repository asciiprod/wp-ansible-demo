# WordPress Ansible Demo

this playbook installs WordPress on a Debian 13 ("trixie") minimal installation

## Usage

```
 ansible-playbook site.yml
```

## Parameters

- Hosts can be configured in the inventory/ directory.
- HostsVariables (username, password, etc) are in the group_vars directory.
- Inventory path can be configured in the ansible.cfg file.
