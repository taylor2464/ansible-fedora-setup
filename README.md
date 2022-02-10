# Purpose
This is a collection of Ansible tasks that I run whenever I need to reformat my computer to ease the setup. Originally written for Fedora running the Gnome desktop environment.

# References
[cron_module](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/cron_module.html "cron_module")
[dnf_module](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/dnf_module.html "dnf_module")
[flatpak_module](https://docs.ansible.com/ansible/latest/collections/community/general/flatpak_module.html "flatpak_module")
[flatpak_remote_module](https://docs.ansible.com/ansible/latest/collections/community/general/flatpak_remote_module.html "flatpak_remote_module")
[mount_module](https://docs.ansible.com/ansible/latest/collections/ansible/posix/mount_module.html "mount_module")

# Run
Command:
`ansible-playbook -e @setup_secrets.enc --ask-vault-pass -K install_setup.yml`
# Author
Taylor Ivy
