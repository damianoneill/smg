# damianoneill.stm

This role installs [stefanmaric/g](https://github.com/stefanmaric/g). stefanmaric/g is a go version manager. This role retrieves the installer script and executes this for the ansible user.

## Requirements

There are no requirements for this role

## Role Variables

The role variables are defined in [./vars/main.yml](./vars/main.yml).

| name     | required | default     | description     |
| -------- | -------- | ----------- | --------------- |
| g_GOROOT | no       | `$HOME/.go` | GOROOT location |
| g_GOPATH | no       | `$HOME/go`  | GOPATH location |

## Dependencies

N/A

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: damianoneill.g }

## License

MIT

## Author Information

- github.com/damianoneill
