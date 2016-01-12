# Minimal working example php CodingStandard

```bash
composer install
cp CodeSniffer.conf vendor/squizlabs/php_codesniffer/
vendor/bin/phpcs --config-set installed_path <path_to_project>
vendor/bin/phpcs --standard=CodingStandard -p TestClass.php
```

```bash
FILE: /tmp/cs/TestClass.php
----------------------------------------------------------------------
FOUND 1 ERROR AFFECTING 1 LINE
----------------------------------------------------------------------
 8 | ERROR | Private member variable "foo" must be prefixed with an
    |       | underscore
    ----------------------------------------------------------------------

Time: 7ms; Memory: 2.25Mb
```