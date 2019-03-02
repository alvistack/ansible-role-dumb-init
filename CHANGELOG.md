# Ansible Role for dumb-init

## 2.4.0 - TBC

### Major Changes

  - Rollback to direct download binary, skip python dependency
  - Add openSUSE Leap 15 support
  - Remove CentOS 6 support

## 2.3.0 - 2019-01-30

### Major Changes

  - Porting test to Molecule based

## 2.2.0 - 2019-01-25

  - Minor typo fix

## 2.1.0 - 2018-12-06

### Major Changes

  - CI with yamllint, ansible-lint and ansible-playbook --syntax-check
  - CI with LXD, improve systemd support
  - Use shell only when shell functionality is required
  - Install dumb-init from PIP, simplify upgrade path

## 2.0.0 - 2018-10-25

### Major Changes

  - Upgrade Ansible support to 2.6 or higher
  - Support both Ubuntu 16.04/18.04 and RHEL/CentOS 6/7
  - Upgrade dumb-init to v1.2.2
  - Update Travis CI test plan

## 1.1.0 - 2017-11-23

### Major Changes

  - Install dumb-init on Ubuntu 16.04/14.04 and CentOS 7/6 from source
  - Update test cases

## 1.0.0 - 2017-09-25

  - Ininitial release for Ansible 2.4
  - Support both Ubuntu 16.04/14.04 or RHEL/CentOS 7/6
