# About
This is a Magento 2 - Blog module created as a composer submodule.

# Requirements

- Magento Composer Installer: To copy the module contents under app/code/ folder.
In order to install it run the below command on the root directory:

        composer require magento/magento-composer-installer

- Add the VCS repository: So that composer can find the module. Add the following lines in your composer.json

        "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/deepakcedcoss/magento2blog"
        }],


# Installation

- Add the module to composer:

        composer require ced/magento2-blog-module

- Add the new entry in `app/etc/config.php`, under the 'modules' section:

        'Ced_Blog' => 1,

- Clear cache

# Usage

        http://yourstore/helloworld/index/


Feel free to contribute, and contact me for any issues.
