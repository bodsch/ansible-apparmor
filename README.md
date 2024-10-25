
# Ansible Role:  `apparmor`

disable and remove apparmor


[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/bodsch/ansible-apparmor/main.yml?branch=main)][ci]
[![GitHub issues](https://img.shields.io/github/issues/bodsch/ansible-apparmor)][issues]
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/bodsch/ansible-apparmor)][releases]
[![Ansible Downloads](https://img.shields.io/ansible/role/d/bodsch/apparmor?logo=ansible)][galaxy]

[ci]: https://github.com/bodsch/ansible-apparmor/actions
[issues]: https://github.com/bodsch/ansible-apparmor/issues?q=is%3Aopen+is%3Aissue
[releases]: https://github.com/bodsch/ansible-apparmor/releases
[galaxy]: https://galaxy.ansible.com/ui/standalone/roles/bodsch/apparmor/


## Operating systems

Tested on

- Debian 10 / 11 / 12
- Ubuntu 20.04 / 22.04


## Contribution

Please read [Contribution](CONTRIBUTING.md)

## Development,  Branches (Git Tags)

The `master` Branch is my *Working Horse* includes the "latest, hot shit" and can be complete broken!

If you want to use something stable, please use a [Tagged Version](https://github.com/bodsch/ansible-apparmor/tags)!


## usage

```yaml
apparmor_state: stopped
apparmor_enabled: false

apparmor_purge: true

apparmor_block:
  later_installation: true
  packages:
    - apparmor
    - apparmor-profiles
    - apparmor-profiles-extra
    - apparmor-notify
    - apparmor-utils
    - dh-apparmor
```

---

## Author and License

- Bodo Schulz

## License

[BSD2](LICENSE)

**FREE SOFTWARE, HELL YEAH!**
