Role common-docker
=========

This is a simple role to install requirements and docker-ce daemon in Centos 7.

Role Variables
--------------

This Role provides append hostlines in /etc/hosts:
  - ip: You might insert your IP List
  - host: You might insert your Host List
 
Dependencies
------------

There is no dependencies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: ansible-common-docker

License
-------

BSD

Author Information
------------------

Alex Mendes https://www.linkedin.com/in/mendesalex/
