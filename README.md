Role Name
=========

A brief description of the role goes here.

Requirements
------------

Needs to run on Ubuntu and just needs Ansible itself installed.

Role Variables
--------------

```yaml
---
# vars file for nginx-webserver
web_server_port: 80
web_server_name: example.com
web_server_config_name: examplecom
nginx_version: 1.22.0-1ubuntu3 
nginx_server_directory: /var/www/{{ web_server_name }}
```

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost 
      become: true
      roles:
        - role: nginx-webserver
          vars:
            web_server_name: demo.example.com
            web_server_config_name: demoexample

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
