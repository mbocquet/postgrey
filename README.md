# postgrey

Ansible role for postgrey, the postfix greylisting policy server.

## Requirements

A running postfix instance.

## Role Variables

Many. See defaults/main.yml.

## Dependencies

You should run a Postfix instance on the host to use this role.

## Install this role as submodule of an existing GIT repository

`git submodule add https://git.sekoya.org/mb/postgrey.git roles/postgrey`

## Example Playbook

    - hosts: servers
      roles:
        - postgrey

or

    - hosts: servers
      roles:
        - { role: postgrey, x: 42 }

if any variables comes in the future for this role.

## License

GPLv3

## Author Information

<a href="http://www.sekoya.org" target="new">http://www.sekoya.org</a>
