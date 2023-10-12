silentsysadmin.update
=========

Perform general updates on linux hosts

Requirements
------------

N/A

Role Variables
--------------

`update_reboot: <true|false>` Permit or deny automatic reboots after patching the host

Dependencies
------------

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: silent-sysadmin.update, update_reboot: true }
    
      tasks:
      ansible.builtin.include_role:
        role: silent-sysadmin.update
        vars:
          update_reboot: true

License
-------

MIT

Author Information
------------------

silentsysadmin.com