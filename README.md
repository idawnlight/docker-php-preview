# What's different?

- Fixed a temporary build issue
  - [Bug #79445: Connection timed out when accessing website from github actions](https://bugs.php.net/bug.php?id=79445)
  - It seems php.net has terminated the mirror project, so I had to use `mirrors.sohu.com`

### Pull

```
$ docker pull metowolf/php
```

### Extension

```
[PHP Modules]
apcu
bcmath
Core
ctype
curl
date
dom
exif
fileinfo
filter
ftp
gd
gettext
gmp
hash
iconv
imagick
intl
json
libxml
mbstring
memcached
mysqli
mysqlnd
openssl
pcntl
pcre
PDO
pdo_mysql
pdo_pgsql
pdo_sqlite
pgsql
Phar
posix
readline
redis
Reflection
session
shmop
SimpleXML
soap
sockets
sodium
SPL
sqlite3
standard
swoole
sysvsem
tidy
tokenizer
xml
xmlreader
xmlrpc
xmlwriter
xsl
Zend OPcache
zip
zlib

[Zend Modules]
Zend OPcache
```
