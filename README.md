Role Name
========

This role installs Composer from https://getcomposer.org

Requirements
------------

This role requires Ansible 1.2 or higher and platform requirements are listed in the metadata file.

Role Variables
--------------

You can override the following variables:

    # Url to download the composer executable from
    composer_download_url: https://getcomposer.org/composer.phar

    # Force the download on every run
    composer_download_force: no

Dependencies
------------

none

License
-------

BSD

Author Information
------------------

Sergey Fayngold