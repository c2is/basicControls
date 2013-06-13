basicControls
=============

Some behat features to launch very basic controls against a website

#Installation

```code
git clone git@github.com:c2is/basicControls.git
cd basicControls
curl -sS https://getcomposer.org/installer | php
php ./composer.phar install
```

#Usage

Define the website url to test in your shell :
```code
BEHAT_PARAMS="context[parameters][base_url]=http://localhost"
```
