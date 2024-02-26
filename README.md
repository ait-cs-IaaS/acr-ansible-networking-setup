# Ansible-Role: acr-ansible-networking-setup

AIT-CyberRange: Applys the set network configuration.


## Requirements

- Debian or Ubuntu 

## Role Variables

```yaml
if_setup: /root/ifsetup.sh

```

## Example Playbook

```yaml
- hosts: localhost
  roles:
    - acr-ansible-networking-setup
      vars:
        if_setup: /root/ifsetup.py
```

## License

GPL-3.0

## Author

- Lenhard Reuter