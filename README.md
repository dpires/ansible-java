[![Build Status](https://travis-ci.org/dpires/ansible-java.svg)](https://travis-ci.org/dpires/ansible-java)

ansible-java
=========

An Ansible role for java

Requirements
------------

N/A

Role Variables
--------------

 - `java.version` The version of Java to install (7,8), defaults to `8`

Dependencies
------------

N/A

Example Playbook
----------------

```
    - hosts: all 
      roles:
         - { role: dpires.java }
```

License
-------

MIT

Author Information
------------------

David Pires
