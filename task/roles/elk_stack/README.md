elk_stack
=========

Ansible Role which would install elk_stack on remote host with default configurations

Requirements
------------

. You have connection to remote side
. The ansible user has privileges to run priviliged tasks
. Pakacge list that is needed(docker, docekr-compose, git)
. write ansible playbook for role and run it

Role Variables
--------------

. No Variables

Dependencies
------------

. No Dependencies

Example Playbook
----------------


    - hosts: servers
      become: yes
      roles:
         - elk_stack

License
-------

BSD

Author Information
------------------

Name: Tigran Sargsyan
Email: tigransargsyan222@gmail.com
GItHub: https://github.com/tigran222
