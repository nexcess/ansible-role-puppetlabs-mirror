# Ansible Role: Puppet Labs Mirror

Installs the Puppet Labs mirroring role

## Requirements

None.

## Role Variables

See `defaults/main.yml`.

## Dependencies

nexcess.mirror

## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-puppetlabs-mirror.git
      name: nexcess.puppetlabs-mirror

## Example Playbook

    - hosts: servers
      roles:
        - nexcess.puppetlabs-mirror

## License

MIT / BSD
