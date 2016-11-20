Role Name
=========

Fish -- finally, a friendly interactive shell for the 90's!

Many fish plays exist on Ansible Galaxy, but few are designed for Debian. This one is. It's not as fully-featured as https://github.com/SobanVuex/ansible-fish but it works.

Requirements
------------

A host running Debian.

To Do
-----------

Extend for Alpine

Role Variables
--------------

The only role variable is the user for whom to set Fish as the default shell.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: djcf.fish, fish_users: ['vagrant'] }

License
-------

GPL
