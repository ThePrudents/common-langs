Common-langs role
=================

This role containes a collection of languages which can be installed.

Role Variables
--------------

By default this role will not install any language if any of the following variables are not set to true:

    install-js
    install-python
    install-jdk
    install-jre
    install-sbt

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: ThePrudents.common-langs
           install-js: true
           install-python: true
           install-jdk: true
           install-jre: false
           install-sbt: false

License
-------

MIT
