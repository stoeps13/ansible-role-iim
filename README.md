ansible-role-iim
=========

Install and update IBM Installationmanager as non-root user.

Requirements
------------

You need to have the installation package downloaded and provide it through the variable `iim_installerpackage`. So give a local path, web url or nfs share.

Role Variables
--------------

User (non-root) who installs the software

    ibm_user: wasuser

Target path for installation

    install_root: /opt/IBM

Zip file with installation files incl path or protocol ie. http://server/agent.installer.linux.gtk.x86_64_1.9.1003.20200730_2125.zip or a local path. The package needs a login for download, so no direct link is possible.

    iim_installerpackage: /mnt/d/software/agent.installer.linux.gtk.x86_64_1.9.1003.20200730_2125.zip

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: stoeps13.ansible-role-iim }

License
-------

Apache-2.0

Author Information
------------------

* Author: Christoph Stoettner
* Blog:   https://stoeps.de