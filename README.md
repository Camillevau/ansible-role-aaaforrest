Role Name
=========

Install AAA For Rest node service https://github.com/Hypertopic/AAAforREST/

Requirements
------------

Node installed.

Role Variables
--------------

custom_config_template (optional): path of a template

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: camillevau.aaaforrest, custom_config_template: /etc/myconfig.json }

License
-------

BSD

Author Information
------------------

Visit http://hypertopic.org