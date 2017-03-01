ansible-sshd-hosts
=========

Ansible playbook to control /etc/hosts.allow & /etc/hosts.deny for sshd service.

Requirements
------------

For ansible `ipaddr` filter
```bash
pip install netaddr
```

Role Variables
--------------

```yaml
---
# defaults file for ansible-sshd-hosts
hosts_allow: []
hosts_deny: []
```

Dependencies
------------

None.

License
-------

BSD

Author Information
------------------

Twitter: @ernestas_poskus
