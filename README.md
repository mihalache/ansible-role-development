Development Role
=========

Easy way to prepare your environment for development.

Requirements
------------

N/A

Role Variables
--------------

samba_user: "vagrant" - the user to use for samba (it must be a system user)
samba_pass: "" - the password for samba (if empty, the password will be the same as the user)

git_config_email - the email to be set in GIT global configuration
git_config_name - the name to be set in GIT global configuration

ssh_keys_user: "vagrant"
ssh_keys_private_key_path: ""
ssh_keys_public_key_path: ""

Dependencies
------------

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: welink.development }

License
-------

BSD

Author Information
------------------

Adrian Mihalache
https://github.com/mihalache
