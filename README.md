## insync

[![CI](https://github.com/Oefenweb/ansible-insync/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-insync/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-insync-blue.svg)](https://galaxy.ansible.com/Oefenweb/insync/)

Set up [Insync](https://www.insynchq.com) in Debian-like systems.

#### Requirements

* `software-properties-common` (will be installed)
* `dirmngr` (will be installed)
* `apt-transport-https` (will be installed)

* `apt-utils` (will be installed)
* `procps` (will be installed)

#### Variables

None

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.insync
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-insync/issues)!
