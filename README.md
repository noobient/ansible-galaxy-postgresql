# noobient.postgresql

## Synopsys

This role installs and configures PostgreSQL instances.

## Parameters

| Name | Required | Example | Description |
|---|---|---|---|
| `version` | no | `17` | PostgreSQL version to be installed. Defaults to `18`. |
| `enabled` | no | `true` | Auto-start PostgreSQL upon boot or not. Defaults to `false`. |
| `port` | no | `5555` | Set port to listen on. Defaults to `5432`. |

## Examples

```yml
- include_role:
    name: noobient.postgresql
  vars:
    version: 17
    enabled: true
    port: 6789
```

## Return Values

N/A

## Support

| Platform | Support | Status |
|---|---|---|
| Linter | ✅ | [![Lint](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/lint.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/lint.yml) |
| AlmaLinux 8 | ✅ | [![AlmaLinux 8](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/almalinux-8.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/almalinux-8.yml) |
| AlmaLinux 9 | ✅ | [![AlmaLinux 9](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/almalinux-9.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/almalinux-9.yml) |
| AlmaLinux 10 | ✅ | [![AlmaLinux 10](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/almalinux-10.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/almalinux-10.yml) |
| Fedora 42 | ✅ | [![Fedora 42](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/fedora-42.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/fedora-42.yml) |
| Fedora 43 | ✅ | [![Fedora 43](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/fedora-43.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/fedora-43.yml) |
| Ubuntu 22.04 | ✅ | [![Ubuntu 22.04](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/ubuntu-22.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/ubuntu-22.04.yml) |
| Ubuntu 24.04 | ✅ | [![Ubuntu 24.04](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/ubuntu-24.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/ubuntu-24.04.yml) |
| Ubuntu 26.04 | ✅ | [![Ubuntu 26.04](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/ubuntu-26.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/ubuntu-26.04.yml) |
