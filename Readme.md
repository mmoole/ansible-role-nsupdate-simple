About
-----

Ansible role for installing a service(timer) that updates the dns server for the host with the hosts hostname. Useful for a host configured with static ip if you want to connect to it using its hostname.
...

Installation
------------
```bash
...
```

Variables
---------

Variables with examples:

```yml
# user for running the service as
nsupdate_user: nsupdate

# default installation path without trailing /
nsupdate_installation_path: /usr/bin

# time to live for the sent record in seconds. Shoul dbe greater than 60.
nsupdate_ttl: 86400
```

Usage
-----

```yml
roles:
  - nsupdate-simple
```


Requirements
------------

This role depends on some external tools:

*	...
