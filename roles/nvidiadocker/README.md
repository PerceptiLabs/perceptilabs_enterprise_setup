Role Name
=========

nvidiadocker

Requirements
------------

none

Role Variables
--------------

- `apt_sources_url` is the package repo where you will pull your nvidia-container-runtime from
- `gpg_key_url` is the gpg source for the package repo

Dependencies
------------

docker_on_ubuntu and nvidia_drivers_from_runfile, both in this repo

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: nvidiadocker

License
-------

CC-BY-4.0
