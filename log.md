
## Day 1
- Set up WSL2 Ubuntu 26.04
- Installed Docker Engine (no Docker Desktop, avoided the license)
- Ran hello-world successfully
## Day 2 — Linux Upskill Day 1
- Explored filesystem: /etc (config), /var/log (logs), /home (users)
- Ubuntu 26.04, kernel <paste from uname -a>, <X>G disk free
- Learned: ls -la columns, man, less (q to quit), ps aux
## Day 3 — Linux Upskill Day 2 (navigation)
- wc -l /etc/passwd → <N> accounts (mostly service accounts, least-privilege)
- .conf files: resolv.conf (DNS), sshd_config (SSH server), logrotate.conf (log rotation)
- Navigation: .. = up, ~ = home (fewest steps), - = previous dir
## Day 4 - Linux Upskill Day 3 (users, groups, sudo)
- User = one account that owns files/processes; group = named set of users sharing permissions
- A user outside the sudo group is refused: "testuser is not in the sudoers file"
- Created and deleted a user (adduser/deluser --remove-home) and a group (groupadd/groupdel)
- usermod -aG: -a appends, without it you replace all groups
