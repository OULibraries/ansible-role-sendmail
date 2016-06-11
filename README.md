OULibraries.sendmail
=========

Sendmail via authenticated SMTP.

Requirements
------------

CentOS/RHEL 7

Role Variables
--------------

```
smtp_host: smtp.example.com
smtp_port: 587
smtp_domain: example.com
smtp_authuser: me@example.com
smtp_authpassword: myemailpassword
sendmail_users:
  - apache
  - root
```

Dependencies
------------


Example Playbook
----------------


License
-------

TBD

Author Information
------------------

Jason Sherman
