# ansible-arch-linux

[![CI](https://github.com/loganmarchione/ansible-arch-linux/actions/workflows/main.yml/badge.svg)](https://github.com/loganmarchione/ansible-arch-linux/actions/workflows/main.yml)

Ansible playbook to setup my Arch Linux desktop (i.e., meant to be run against localhost)

## Requirements

1. Install the necessary packages `sudo pacman -S ansible git python`
1. Install the Ansible requirements `ansible-galaxy collection install community.general`
1. Clone this repo `https://github.com/loganmarchione/ansible-arch-linux.git`
1. (Optional) Run the playbook in check mode to view potential changes `ansible-playbook main.yml --ask-become-pass --check`
1. Run the playbook `ansible-playbook main.yml --ask-become-pass`

## TODO
- [ ] Add reflector pacman hook
