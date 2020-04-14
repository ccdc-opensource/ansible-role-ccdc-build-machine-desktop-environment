ccdc-desktop-environment
========================

A role to set up a test-suitable desktop environment. This will set up the following on Linux, macOS and Windows:

  * (CentOS only) Install the GNOME Desktop Environment and make it the default boot environment
  * (Ubuntu only) Install the Ubuntu desktop environment and make it the default boot environment
  * Set up automatic login for the `vagrant` user
  * Disable screen locks and screensavers

Example Playbook
----------------

```yaml
- hosts: all
  roles:
      - ccdc-buildmachine-desktop-environment
```

Example requirements.yml lines for ansible-galaxy
-------------------------------------------------

```yaml
# Set up desktop environment for test machines
- src: git@ssh.dev.azure.com:v3/ccdc/build-systems/ansible-role-ccdc-buildmachine-desktop-environment
  scm: git
  name: ccdc-buildmachine-desktop-environment
```

License
-------
CCDC Internal. Do not distribute.

