Development Role
=========

Easy way to prepare your environment for development.

Requirements
------------

N/A

Role Variables
--------------
```samba_share_name: project``` the name of the samba share (you will connect to the share with __\\\ip.address\share_name__)

```samba_shared_folder: /var/www/``` the name of the shared folder (it will be created if not exists)

```samba_shared_folder_owner: vagrant``` the name of the shared folder owner

```git_config_name: ""``` the name to be set in GIT global configuration

```git_config_email: ""``` the email to be set in GIT global configuration

Dependencies
------------

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: ansible-role-development }

License
-------

BSD

Author Information
------------------

Adrian Mihalache
https://github.com/mihalache
