Imagemagick from source
=========

The role was built for personal purposes. I needed a quantum-depth option that differs from the default 16.
Didn't find the role to built imagemagick from source, so introduced my own.

Role Variables
--------------

1st ver is simple and doesn't offer user a lot of configurable options.

    imagemagick_version: "ver number"

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: igkuz.imagemagick-from-source, imagemagick_version: "6.9.3-1", quantum_depth: 8 }

License
-------

MIT
