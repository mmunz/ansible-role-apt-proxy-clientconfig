c1.apt-proxy-clientconfig
=========================

Configures an apt proxy.

Role Variables
--------------

- apt_proxy_clientconfig_url - false (no proxy use, default) or url of the apt proxy to use

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: c1.apt-proxy-clientconfig
           apt_proxy_clientconfig_url: http://apt-proxy:3128

License
-------

BSD
