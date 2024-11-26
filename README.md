# noobient.postgresql

## Synopsys

This role installs and configures PostgreSQL instances.

## Parameters

| Name | Required | Example | Description |
|---|---|---|---|
| `version` | no | `16` | PostgreSQL version to be installed. Defaults to `17`. |

## Examples

```yml
- include_role:
    name: noobient.postgresql
  vars:
    version: 16
```

## Return Values

N/A

## Support

| Platform | Support | Status |
|---|---|---|
| Linter | ✅ | [![Lint](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/lint.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/lint.yml) |
| AlmaLinux 8 | ✅ | [![AlmaLinux 8](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/almalinux-8.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/almalinux-8.yml) |
| AlmaLinux 9 | ✅ | [![AlmaLinux 9](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/almalinux-9.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/almalinux-9.yml) |
| Fedora 40 | ✅ | [![Fedora 40](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/fedora-40.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/fedora-40.yml) |
| Fedora 41 | ✅ | [![Fedora 41](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/fedora-41.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/fedora-41.yml) |
| Ubuntu 20.04 | ✅ | [![Ubuntu 20.04](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/ubuntu-20.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/ubuntu-20.04.yml) |
| Ubuntu 22.04 | ✅ | [![Ubuntu 22.04](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/ubuntu-22.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/ubuntu-22.04.yml) |
| Ubuntu 24.04 | ✅ | [![Ubuntu 24.04](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/ubuntu-24.04.yml/badge.svg)](https://github.com/noobient/ansible-galaxy-postgresql/actions/workflows/ubuntu-24.04.yml) |
