Role Name
=========

A role to downlaod the tika jar file

Requirements
------------

None

Role Variables
--------------

The vars are used to construct the download

  tika_version: '1.8'
  tika_mirror: 'http://archive.apache.org/dist/tika'

Dependencies
------------
None - but expects to have SOLR to be any use.

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: apache-tika }

License
-------

BSD

Author Information
------------------

Blue-Bag / Miggle
