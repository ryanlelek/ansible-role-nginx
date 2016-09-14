Nginx
=====

Installs Nginx Package from official repos

Requirements
------------

Tested on Ubuntu.  
**See Also: [ryanlelek.site](https://github.com/ryanlelek/ansible-role-site)**

Dependencies
------------
None

Example Playbook
----------------

    - hosts: web
      roles:
         - ryanlelek.nginx
         # Optional, Default Site
         - ryanlelek.site
           site_domain: default
           site_redirect: https://www.google.com

License
-------

MIT

Author Information
------------------

Created by [Ryan Lelek](https://www.ryanlelek.com)  
Part of [AnsibleTutorials.com](http://www.ansibletutorials.com)
