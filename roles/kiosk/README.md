Role Name
=========

Setup kiosk mode for Alpine Linux

Requirements
------------

apk add python3


Role Variables
--------------

Browser - select between firefox and chromium
Url - The link that the browser will follow
User - The user from which kiosk will be run

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.
ansible-galaxy collection install community.general

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
       - kiosk

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
