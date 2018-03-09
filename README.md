# postgrey

Ansible role for postgrey, the postfix greylisting policy server.

## Requirements

A running postfix instance.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

    - hosts: servers
      roles:
        - mbocquet.postgrey

or

    - hosts: servers
      roles:
        - { role: mbocquet.postgrey, x: 42 }

if any variables comes in the future for this role.

## License

GPLv3

## Author Information

<a href="http://www.sekoya.org" target="new">http://www.sekoya.org</a>
