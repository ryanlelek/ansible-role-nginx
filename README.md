Nginx
=====

Installs Nginx Package from official repos

Requirements
------------

Tested on Ubuntu.  
See Also: ryanlelek.nginx_site

Role Variables
--------------

Change the redirect URL when no sites match:  
- **redirect_url**: https://www.google.com

Dependencies
------------

None

Example Playbook
----------------

    - hosts: web
      roles:
         - ryanlelek.nginx

License
-------

MIT

Author Information
------------------

Created by [Ryan Lelek](https://www.ryanlelek.com)  
Part of [AnsibleTutorials.com](http://www.ansibletutorials.com)
