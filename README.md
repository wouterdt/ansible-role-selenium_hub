Role Name
=========

Installs a selenium hub on RedHat/Centos 7
Requirements
------------

 Requires access to Internet to download the selenium binary, source can however be overriden by variable

Role Variables
--------------

All variables specified in https://github.com/SeleniumHQ/selenium/blob/master/java/server/src/org/openqa/grid/common/defaults/DefaultHub.json  are configurable, see defaults/mail.yml

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

GPLv2