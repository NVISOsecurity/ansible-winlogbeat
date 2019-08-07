# ansible-winlogbeat

Ansible role for installing and configuring WinLogBeat

## WinLogBeat Configuration

The role applies the [Malware Archeology WinLogBeat configuration file](https://www.malwarearchaeology.com/s/winlogbeat-8e78.yml).

## OS Platforms

This role has been tested on the following operating systems:

- Ubuntu 18.04

## Usage

To use this role in your playbook, add the code below:

```
- name: Install WinLogBeat
  import_role:
    name: ansible-winlogbeat
```

## Disclaimer

This role is meant for use in the SANS 699 course and is provided as is.

## License

[MIT](LICENSE)