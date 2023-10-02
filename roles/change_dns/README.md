change_dns
=========

A role that will change_dns on remote host

Requirements
-----------

. Ensure you have connection to remote host
. Change dns nameserver IP address what would you like in tasks/main.yml file
. write ansible-playbook for role and run it 

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
         - change_dns

License
-------

BSD

Author Information
------------------

Name: Tigran Sargsyan
Email: tigransargsyan222@gmail.com
GitHub: https://github.com/tigran2222
