Ansible Apache role
=========

Install and configure [apache2](https://httpd.apache.org/) with self signed certificate.

Role variables
---
Available variables are listed below, along with default values in `vars/main`:
```
apache_server_name: "{{ ansible_fqdn }}"
document_root: /var/www/html
admin_mail: admin@example.com
```

Dependencies
--------------
None

Example Playbook
--------------
```
- hosts: localhost
  roles:
    - myckakamil.snmpd
```

Author Information
--------------
This role was created in 2025 by [Kamil Myćka](https://github.com/myckakamil)
