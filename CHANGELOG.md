# Ansible Role for ceph-mds

## 4.3.0 - TBC

### Major Changes

## 4.2.0 - 2020-02-13

### Major Changes

  - Migrate molecule driver to Libvirt
  - Migrate molecule verifier to Ansible
  - Support Ubuntu 19.10

## 4.1.0 - 2020-01-16

### Major Changes

  - Default `interpreter_python` with `python3`
  - Bugfix `python3-xml` not exists for openSUSE Leap 15.1

## 4.0.0 - 2019-11-05

### Major Changes

  - Upgrade minimal Ansible support to 2.9.0
  - Upgrade Travis CI test as Ubuntu Bionic based

## 3.5.0 - 2019-10-06

### Major Changes

  - Support openSUSE Leap 15.1
  - Default with Python 3
  - Revamp molecule test with vagrant

## 3.4.0 - 2019-09-18

### Major Changes

  - Run molecule test manually on Travis CI

## 3.3.0 - 2019-08-27

### Major Changes

  - Update for RHEL 7
  - Add Vagrant test for RHEL 7
  - Restart service serially

## 3.2.0 - 2019-07-08

### Major Changes

  - Update LXD test profile for Kubernetes v1.15.0 support
  - Fix molecule `group_vars` with links
  - Replace `with_items` with `loop`
  - Replace `with_dict` with `var`
  - Replace `with_first_found` with `lookup('first_found')`
  - Update Vagrant test with `private_network`

## 3.1.0 - 2019-06-13

### Major Changes

  - Always include default variables from `vars/main.yml`
  - Always use `become: true` with molecule, especially for vagrant
  - Better multinode test cases

## 3.0.0 - 2019-05-28

  - Initial release for Ansible 2.8 or higher
  - Support both Ubuntu 16.04/18.04 or RHEL/CentOS 7 or openSUSE Leap 15
