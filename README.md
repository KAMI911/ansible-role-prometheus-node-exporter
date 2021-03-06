# Ansible Role: Installs Prometheus Node Exporter

Installs Prometheus Node Exporter

[![Build Status](https://travis-ci.org/KAMI911/ansible-role-spcewalk.svg?branch=master)](https://travis-ci.org/KAMI911/ansible-role-prometheus-node-exporter)

## Table of Contents

1. [Requirements][Requirements]
2. [Installation][Installation]
3. [Role Variables][Role Variables]
4. [Dependencies][Dependencies]
5. [Example Playbook][Example Playbook]
6. [Licensing][Licensing]
7. [Author Information][Author Information]
8. [Support][Support]
9. [Contributing][Contributing]
10. [Donation][Donation]

## Requirements

None.

## Role Variables


## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - prometheus-node-exporter

## Licensing

The Prometheus Node Exporter Role application and documantations are licensed under the terms of the MIT / BSD, you will
find a copy of this license in the [LICENSE](LICENSE) file included in the source package.

## Author Information

This role was created in 2019-2020 by Kálmán Szalai - KAMI

## Support

If you have any question, do not hesitate and drop me a line.
If you found a bug, or have a feature request, you can [fill an issue](https://github.com/KAMI911/ansible-role-prometheus-node-exporter/issues).

### Using as a submudule of an AWX playbook

#### Add as a submodule

```
git submodule add --force git@github.com:KAMI911/ansible-role-prometheus-node-exporter.git roles/prometheus-node-exporter
```

#### Update as sumodule

Update only this submodule

```
git submodule update --remote roles/prometheus-node-exporter/
```

Update all submodules:

```
git submodule foreach git pull origin master
```

## Contributing

There are many ways to contribute to ansible-role-prometheus-node-exporter -- whether it be sending patches,
testing, reporting bugs, or reviewing and updating the documentation. Every
contribution is appreciated!

Please continue reading in the [contributing chapter](CONTRIBUTING.md).

### Fork me on Github

https://github.com/KAMI911/ansible-role-prometheus-node-exporter

Add a new remote `upstream` with this repository as value.

```
git remote add upstream https://github.com/KAMI911/ansible-role-prometheus-node-exporter.git
```

You can pull updates to your fork's master branch:

```
git fetch --all
git pull upstream HEAD
```

## Donation

If you find this useful, please consider a donation:

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RLQZ58B26XSLA)

<!-- TOC URLs -->
[Requirements]: #requirements
[Installation]: #installation
[Role Variables]: #role_variables
[Dependencies]: #dependencies
[Example Playbook]: #example_playbook
[Licensing]: #licensing
[Author Information]: #author_information
[Support]: #support
[Contributing]: #contributing
[Donation]: #donation
