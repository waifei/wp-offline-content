# wp-offline
> Offline reading for WordPress.

[![Build Status](https://travis-ci.org/delapuente/wp-offline.svg?branch=master)](https://travis-ci.org/delapuente/wp-offline)

## Install the plugin

Clone the repository and copy the folder `wp-offline` inside your WordPress `plugins` directory.

Activate the plugin from the _Plugins_ menu in the _Dashboard_. Options are available to customize under the _Offline content_ submenu in _Settings_.

## Running tests

Install dependencies:
```bash
./install-wp-tests.sh MYSQL_DATABASE_NAME MYSQL_USER MYSQL_PASSWORD localhost latest
```

Run tests:
```bash
make test
```

Run service worker tests:
```bash
make test-sw
```
