# nephelaiio.zip

[![Build Status](https://travis-ci.org/nephelaiio/ansible-role-zip.svg?branch=master)](https://travis-ci.org/nephelaiio/ansible-role-zip)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-systemd--service-blue.svg)](https://galaxy.ansible.com/nephelaiio/zip/)

An [ansible role](https://galaxy.ansible.com/nephelaiio/zip) to install and configure zip

## Role Variables

Please refer to the [defaults file](/defaults/main.yml) for an up to date list of input parameters.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
    - hosts: servers
      roles:
         - role: nephelaiio.zip
```

## Testing

Role is tested against the following distributions (docker images):
  * Ubuntu Xenial
  * CentOS 7
  * Debian Stretch
  * Arch Linux

You can test the role from sources from the command line using molecule directly ` molecule test `

## License

This project is licensed under the terms of the [MIT License](/LICENSE)
