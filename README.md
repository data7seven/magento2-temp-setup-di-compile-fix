Thanks to hostep for finding this workaround.

I packaged it so its easy to add to your magento2 install.


Used with Magento 2.1.0 GA to fix upgrade issues / deployment.


## Install:

```
composer require peec/magento2-temp-setup-di-compile-fix
bin/magento module:enable Peec_TempSetupDiCompileFix
```
