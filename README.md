OULibraries.sendmail
=========

TLS-encrypted sendmail via authenticated SMTP.

Requirements
------------

CentOS/RHEL 7

Role Variables
--------------

```
smtp_host: smtp.example.com
smtp_port: 587
smtp_domain: example.com
smtp_start_tls: YES
smtp_from_line_override: YES
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
