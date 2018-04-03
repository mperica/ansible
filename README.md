# Ansible Example

[![Platforms](https://img.shields.io/badge/platform-ubuntu,amazonlinux-lightgrey.svg?style=flat)](#)

This is example of ansible configuration for AWS it uses tag "web" to distribute to all servers with tag Name=web.
In this example ansible installes AWS CodeDeploy Agent on AmazonLinux but it can also install on any RedHat based distro or Debian based like Ubuntu.


### Config
------------

This setup uses AWS environment variables so first chech if you have them.
"echo $AWS_ACCESS_KEY_ID"
"echo $AWS_SECRET_ACCESS_KEY"

- ansible.pem | Change key for your own or update the file.
- group_vars/all.yml | Change to reflect your data
- site.yml | Change tag name for your configuration

Read roles Readme for any other configuration.

### License
-------

All Rights Reserved

### Author Information
------------------

* [Martin Perica](mailto:martinperica0@gmail.com)
