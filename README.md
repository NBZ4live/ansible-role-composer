[![Build Status](https://travis-ci.org/NBZ4live/ansible-role-composer.png?branch=master)](https://travis-ci.org/NBZ4live/ansible-role-composer)

Composer
========

This role installs Composer from https://getcomposer.org

Requirements
------------

This role requires Ansible 1.2 or higher and platform requirements are listed in the metadata file.

Role Variables
--------------

The role uses the following variables:

 - **composer_download_url**: Defines the download url of the composer.phar.
  Defaults to ```https://getcomposer.org/composer.phar```.
 - **composer_download_force**: Forces the download on every run.
  Defaults to ```no```.

Global Variables
--------------
This variables are without a namespace to be used across the entire playbook
 - **apt_cache_valid_time**: Used for ```cache_valid_time``` in the apt module.
  Defaults to ```86400```

Example usage
-------

    ---
    # file: task.yml
    - hosts: all
      roles:
        - nbz4live.composer

Dependencies
------------

none

License
-------

BSD

Author Information
------------------

- Sergey Fayngold <sergey@faynhost.com>