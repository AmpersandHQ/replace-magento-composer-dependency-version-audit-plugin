# replace-magento-composer-dependency-version-audit-plugin


If we have two packages replacing this they cannot coexist due to this error

```
They both replace magento/composer-dependency-version-audit-plugin and thus cannot coexist.
```

We can make all our projects/packages require this module in instead and ensure this package is removed everywhere

See https://github.com/magento/composer-dependency-version-audit-plugin/issues/6
