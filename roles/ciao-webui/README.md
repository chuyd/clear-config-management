# clearlinux.ciao-webui
This role installs clearlinux/ciao-webui docker container

## Requirements
Docker

## Role variables

Variable  | Default Value | Description
--------  | ------------- | -----------
keystone_fqdn | `{{ ansible_fqdn }}` | Hostname of the identity host
ciao_webui_fqdn | `{{ ansible_fqdn }}` | Hostname of the webui host

## Dependencies
None

## Example playbook
file *ciao.yml*
```
- hosts: controllers
  roles:
    - clearlinux.ciao-webui
```

## Contribution
**Pull Requests and Issues should be opened at [clearlinux/clear-config-management](https://github.com/clearlinux/clear-config-management).**

## License
Apache-2.0

## Author Information
This role was created by [Erick Cardona](erick.cardona.ruiz@intel.com)
