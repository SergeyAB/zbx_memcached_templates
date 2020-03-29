## Requirements
Template items uses telnet connection, so Memcached have to be configured to use network.
Unix socket disables network support.

## Installation
- Put `userparameter_memcached.conf` into UserParameter's directory.
- On the zabbix server web page import XML template file.

Change macroses `{$MEMCACHED_SERVER}` and `{$MEMCACHED_PORT}` if you need.

Use IP address instead of hostname in `{$MEMCACHED_SERVER}`.

## References
- Userparameters based on https://share.zabbix.com/databases/memcache/memcached-template-for-zabbix-3-4
- Items based on official Memcached manual https://github.com/memcached/memcached/blob/master/doc/protocol.txt

