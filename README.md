# cara install OpenLiteSpeed + PHP + Mariadb dari source-nya
```code
apt update && sudo apt install -y build-essential autoconf pkg-config libxml2-dev libcurl4-openssl-dev libsqlite3-dev libonig-dev libssl-dev libkrb5-dev libldap2-dev libgmp-dev libpspell-dev libtidy-dev zlib1g-dev libxslt1-dev libpq-dev libfreetype6-dev libzip-dev libsodium-dev libc-client-dev
```
downloda dan install dgn perintah ini
```code
./configure --prefix=/usr/local/lsws/lsphp83 --enable-bcmath --with-pear --with-kerberos \
--enable-calendar --enable-ctype --with-curl --enable-exif --enable-fileinfo --enable-filter \
--enable-ftp --with-gettext --with-gmp --with-iconv --with-imap --with-imap-ssl --with-ldap \
--with-libxml --enable-mbstring --with-mysqli --with-mysql-sock=/var/run/mysqld/mysqld.sock \
--with-pdo-mysql --with-pdo-pgsql --with-pdo-sqlite --enable-phar --enable-posix --with-pspell \
--enable-session --enable-shmop --enable-simplexml --enable-soap --enable-sockets --with-sodium \
--with-sqlite3 --enable-sysvsem --enable-sysvshm --with-tidy --enable-tokenizer --with-xsl \
--enable-xml --enable-xmlreader --enable-xmlwriter --with-zip --with-zlib --enable-litespeed 
```
panduan lengkap di https://www.howtoforge.com/how-to-install-lomp-stack-openlitespeed-mysql-and-php-on-ubuntu-24-04/
