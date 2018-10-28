# Stack

## Overview

With a _Stack_ we provide an other level of simplicity used by the feature _Project_.  
A _Stack_ is a `pile` who can only contain links to public packages \(hosted on [Packagist.org](https://packagist.org)\) and  private packages \(hosted on harmony Marketplace\).

By example, if you choose the database _MongoDB_ for your project, we will link the stack named **MongoDB**. This stack will tell to HarmonyFlex to execute the command `composer config "platform.ext-mongo" "1.6.16"` and install the next packages:

* [alcaeus/mongo-php-adapter](https://packagist.org/packages/alcaeus/mongo-php-adapter)
* [doctrine/mongodb](https://packagist.org/packages/doctrine/mongodb)
* [doctrine/mongodb-odm-bundle](https://packagist.org/packages/doctrine/mongodb-odm-bundle)

