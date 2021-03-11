Common role (for homweork)
==========================

Installs latest vim and zip apps via apt module

Example Playbook
----------------

To use, an example playbook would be:

    - hosts: servers
      roles:
         - common

since this role has `become=yes` in the task itself, no need 
to use it on the playbook level (unless so desired)

License
-------

BSD

Author Information
------------------

www.github.com/whitehawk2
