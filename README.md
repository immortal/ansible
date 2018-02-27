# immortal ansible role

To install immortal via [ansible](https://www.ansible.com/) this role can be
used, example:

```yaml
---
- hosts: all
  become: true
  roles:
    - immortal
```

The current role only working for [FreeBSD](https://freebsd.org) and
[Debian](https://www.debian.org/derivatives/) based Linux operating systems,
help improving is more than welcome.
