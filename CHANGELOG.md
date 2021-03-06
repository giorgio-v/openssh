openssh Cookbook CHANGELOG
==========================
This file is used to list changes made in each version of the openssh cookbook.


v1.2.2
------
### Bug
- **[COOK-3304](https://tickets.opscode.com/browse/COOK-3304)** - Fix error setting Dynamic `ListenAddresses`

v1.2.0
------
### Improvement
- [COOK-2647]: `port_ssh` iptables template has no corresponding recipe

v1.1.4
------
- [COOK-2225] - Add platform_family suse

v1.1.2
------
- [COOK-1954] - Fix attribute camel case to match `man sshd_config`
- [COOK-1889] - SSH restarting on each chef run due to template changes

v1.1.0
------
- [COOK-1663] - Configurable ListenAddress based off list of interface names
- [COOK-1685] - Make default sshd_config value more robust

v1.0.0
------
- [COOK-1014] - Templates for ssh(d).conf files.

v0.8.1
------
- Current public release
