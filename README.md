# magento2-sample-module-minimal-register
Magento 2 - Sample Module - Demonstrating the minimal requirements for using composer to register the module to live inside vendor

## Installation Steps

    composer config repositories.mttjohnson/module-sample-minimal-register git git@github.com:mttjohnson/magento2-sample-module-minimal-register.git
    composer require mttjohnson/module-sample-minimal-register:dev-master --prefer-dist
    bin/magento module:enable Mttjohnson_SampleMinimalRegister --clear-static-content
    bin/magento setup:upgrade


## Breakdown

    composer config repositories.mttjohnson/module-sample-minimal-register git git@github.com:mttjohnson/magento2-sample-module-minimal-register.git


    composer require mttjohnson/module-sample-minimal-register:dev-master --prefer-dist


    bin/magento module:enable Mttjohnson_SampleMinimalRegister --clear-static-content


    bin/magento setup:upgrade
