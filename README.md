Zend Framework
=========

This role will install Zend Framework 1

Requirements
------------

Requires PHP to be installed.

Role Variables
--------------

The version installed can be set with ```zf_version``` variable.

Zend Frameworks installation path can be set with ```zf_path```.

Require statements can be stripped out for optimisation with ```strip_zf_requires```.

Dependencies
------------

No dependencies

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: frontend
      roles:
         - { role: zend-framework, zf_version: 1.12.9 }

License
-------

BSD
