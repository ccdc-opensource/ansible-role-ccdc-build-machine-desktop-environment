ccdc-desktop-environment
========================

A role that installs the standard GNOME desktop environment.

Example Playbook
----------------
- hosts: desktops
  roles:
      - ccdc-desktop-environment

Example requirements.yml lines for ansible-galaxy
--------------------
# Install the CSDS
- src: http://dev.azure/hg/ansible-role-ccdc-desktop-environment
  name: ccdc-desktop-environment

License
-------
CCDC Internal. Do not distribute.

