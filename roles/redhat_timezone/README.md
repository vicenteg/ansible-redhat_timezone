redhat_timezone
=========

A role to set the timezone on a Redhat derived system.

Requirements
------------

Role Variables
--------------

	timezone

Dependencies
------------

Example Playbook
----------------

	- hosts: all
	  roles:
	    - { role: redhat_timezone, timezone: "America/New_York" }

License
-------

MIT

Author Information
------------------

Vince Gonzalez
