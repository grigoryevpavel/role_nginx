Role Name
=========

role_nginx

Description
------------

Role installs nginx and configures default port base on the value of **hostport** variable. 

Role Variables
--------------

| Variable name | Variable description |
|---------------|----------------------| 
| hostport        | Default port number on which nginx-server is accessable |
 
How to install in subfolder **roles** of current project folder
---------------

ansible-galaxy role install --roles-path ./roles git+https://github.com/grigoryevpavel/roles-nginx.git

How to use role
----------------

  - hosts: servers
    roles:
        - { role: role_nginx }

License
-------

MIT

Author Information
------------------

Pavel Grigoryev

