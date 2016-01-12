# Minimal working example php CodingStandard

```bash
composer install
cp CodeSniffer.conf vendor/squizlabs/php_codesniffer/
vendor/bin/phpcs --config-set installed_path <path_to_project>
vendor/bin/phpcs --standard=CodingStandard -p TestClass.php
```
