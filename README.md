ccdc.build_machine_desktop_environment
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
      - ccdc.build_machine_desktop_environment
```

Example requirements.yml lines for ansible-galaxy
-------------------------------------------------

```yaml
# Set up desktop environment for test machines
- name: ccdc.build_machine_desktop_environment
```

License
-------
MIT / BSD

