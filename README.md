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

Note that the sendmail_users var is a bit deceptive, as these local users will be aliased to the authenticated account.
This is handy for getting things working quickly, but it will also overrride any from line that you specify.

Dependencies
------------


Example Playbook
----------------


License
-------

[MIT](https://github.com/OULibraries/ansible-role-sendmail/blob/master/LICENSE)

Author Information
------------------

Jason Sherman
