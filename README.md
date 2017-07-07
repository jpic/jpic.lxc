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



License
-------

BSD
