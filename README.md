ansible-role-iim
=========

Install and update IBM Installationmanager

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

ibm_user: non-root user who installs the software
install_root: target path for installation (default: /opt/IBM)
iim_installerpackage: zip file with installation files incl path or protocol ie. http://server/agent.installer.linux.gtk.x86_64_1.9.1003.20200730_2125.zip or /mnt/d/software/agent.installer.linux.gtk.x86_64_1.9.1003.20200730_2125.zip

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

Apache-2.0

Author Information
------------------

Author: Christoph Stoettner
Email:  christoph.stoettner@stoeps.de
Blog:   https://stoeps.de