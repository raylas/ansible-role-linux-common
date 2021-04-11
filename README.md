Ansible Role: Linux Common
=========

Unrefined and common pattern of basics for RedHat and Ubuntu hosts.

Requirements
------------

A RedHat or Ubuntu host in your inventory.

Role Variables
--------------

`common_packages` - Packages which will install on either distro
`redhat_packages` - Package names unique to RedHat/CentOS
`ubuntu_packages` - Package names unique to Ubuntu


Dependencies
------------

None.

Example Playbook
----------------

Not much to it:
```yaml
- name: Provision LXC container(s)
  hosts: containers
  become: yes

  roles:
  - linux-common
```

License
-------

MIT

Author Information
------------------

This role was created in 2021 by [Raymond Douglas](https://rymnd.org).
