jpic.lxc
========

Setup LXC, Debian and Arch Linux.

Usage
-----

You don't need any configuration for setup lxc, here is an example playbook.

```
---
- hosts: localhost
  become: yes
  roles:
    - jpic.lxc
```


Also, you can take a look at the Vagrantplaybook.yml. That is a full example of how to use this role.


License
-------

BSD
