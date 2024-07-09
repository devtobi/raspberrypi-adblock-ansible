Role Name
=========

This role installs and configures security measurements like unattended upgrades, fail2ban and ufw firewall.

Role Variables
--------------

- `security_auto_reboot_with_users`: Decides whether the system should reboot after unattended upgrade even if a user is connected to the system.
- `security_auto_reboot_time`: Timepoint the system will reboot if a reboot is required by unattended upgrades.
- `security_system_user`: System user to reboot after unattended upgrade.
- `security_allow_ufw_ports`: List of ports to be allowed by the ufw. All other ports will be blocked.

License
-------

MIT

Author Information
------------------

- [@langehm](https://github.com/langehm)
- [@devtobi](https://github.com/devtobi)