# KhulnaSoft Fair Web Analytics for YunoHost

![Install KhulnaSoft Fair Web Analytics with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)

> *This package allows you to install KhulnaSoft Fair Web Analytics quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

KhulnaSoft Fair Web Analytics is an open alternative to common web analytics tools.
Gain insights while your users have full access to their data.
Lightweight, self hosted and free.

**Shipped version:** 0.1.3

## Demo

Run a local demo on your own machine:

```
curl -sSL https://demo.khulnasoft.com | bash
```

## Configuration

Accounts and users can be managed from within KhulnaSoft Fair Web Analytics's admin panel.

## Documentation

 * Official documentation: https://docs.khulnasoft.com

#### Supported architectures

* x86-64

## Limitations

* KhulnaSoft Fair Web Analytics needs to run on a dedicated subdomain.
* KhulnaSoft Fair Web Analytics is public by default.

**More info on the documentation page:**  
https://yunohost.org/packaging_apps

## Links

 * Report a bug: https://github.com/khulnasoft/khulnasoft_ynh/issues
 * App website: https://www.khulnasoft.com
 * Upstream app repository: https://github.com/khulnasoft/khulnasoft
 * YunoHost website: https://yunohost.org/

---

Developer info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please send your pull request to the [testing branch](https://github.com/khulnasoft/khulnasoft_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/khulnasoft/khulnasoft_ynh/tree/testing --debug
or
sudo yunohost app upgrade khulnasoft -u https://github.com/khulnasoft/khulnasoft_ynh/tree/testing --debug
```
