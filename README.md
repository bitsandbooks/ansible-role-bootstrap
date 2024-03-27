# Bootstrap

Common plays for all nodes.

## Requirements

None

## Role Variables

- `default_group_name` and `default_group_gid` are the default group for all nodes
- `default_ssh_port` is the default port on which SSH will listen

## Dependencies

None

## Example Playbook

    - hosts: servers
      roles:
         - bitsandbooks.bootstrap

## License

[GNU General Public License, version 3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)

## Author Information

[Rob Dumas](https://robdumas.com/).
