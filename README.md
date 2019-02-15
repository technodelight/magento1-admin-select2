# Magento1 Admin module to use Select2 plugin everywhere

This is an absolutely simple package which beautifies the input fields a bit + uses select2 on every select input rendered on the site. It will make your life a bit easier.

# Installation
```
composer require technodelight/magento1-admin-select2
```

# Ignore the module and use only for local development

First, reset your composer changes after the installation has been done
```
git reset composer.*
git checkout composer.*
```
Then add the following to `.git/info/exclude`:

```
public/app/code/community/Technodelight/AdminSelect2/
public/app/design/adminhtml/default/default/layout/technodelight_adminselect2
public/app/etc/modules/Technodelight_AdminSelect2.xml
public/skin/adminhtml/default/default/technodelight_adminselect2
```

# Credits
2019 Zsolt Gál (contact me so I can send details on how to buy me a beer)

# License
[OSL v3](http://opensource.org/licenses/OSL-3.0)
