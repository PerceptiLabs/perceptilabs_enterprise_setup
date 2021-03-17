Role Name
=========

perceptilabs_enterprise

Requirements
------------

none

Role Variables
--------------

This role requires the docker_password to be set. It will use it to pull from the registry defined in defaults/docker_registry_url

Dependencies
------------

All dependencies are included

Example Playbook
----------------

- hosts: perceptilabs_servers
  vars_prompt:
    - name: docker_password
      prompt: enter the docker password
      private: yes
  roles:
    - role: perceptilabs_enterprise

License
-------

CC-BY-4.0

Author Information
------------------

This is a product of PerceptiLabs inc. (perceptilabs.com)
