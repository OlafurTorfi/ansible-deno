Ansible Deno
=========

This role installs deno using the provided install script on deno.land.

NOTE: This role downloads a 3rd party script and executes it, which is a potential security risk. Use only if you trust 'https://deno.land'

Role Variables
--------------
deno_install_user
deno_install_path

Dependencies
------------
unzip

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: olafurtorfi.deno }

License
-------
BSD

Author Information
------------------
Author is a software developer from iceland, experimenting with ansible.