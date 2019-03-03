Role Name
=========

Installs a selenium hub on RedHat/Centos 7
Requirements
------------

 Requires access to Internet to download the selenium binary, source can however be overriden by variable

Role Variables
--------------

All variables specified in https://github.com/SeleniumHQ/selenium/blob/master/java/server/src/org/openqa/grid/common/defaults/DefaultHub.json  are configurable, see defaults/mail.yml
download source can be set in selenium_hub_download


Dependencies
------------

None

Example Playbook
----------------
    - hosts: servers
      roles:
         - { role: wouterdt.selenium_hub}

License
-------

GPLv2