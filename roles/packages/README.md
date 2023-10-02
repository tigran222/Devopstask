packages
=========

Role for installing packages on remote Host(Debian based)

Requirements
------------

. Already ready environment
. Be sure you have created ansible.cfg, ansible inventroy file and you have privileged access on your remote hosts(you can try ansible ping on hosts)
. Make Sure to write package_list.txt file in packages/file/ directory with packages names you need
. write ansible-playbook that will run the role

Role Variables
--------------

. There is no any variable

Dependencies
------------

. No Dependencies

Example Playbook
----------------


    - hosts: servers
      become: yes
      roles:
         - packages

License
-------

BSD

Author Information
------------------

Name: Tigran Sargsyan
Email: tigransargsyan222@gmail.com
GitHub: https://github.com/tigran222
