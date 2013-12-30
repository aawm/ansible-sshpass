# ansible-sshpass

This ansible role installs sshpass

## Requirements

This role requires Ansible 1.4 higher and platforms listed in the metadata file.

## Example

    ---
    - hosts: all
      sudo: yes
      roles:
        - role: sshpass
