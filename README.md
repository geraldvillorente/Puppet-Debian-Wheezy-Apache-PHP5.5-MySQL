Puppet Debian Wheezy Apache PHP5.5 MySQL
========================================

Puppet script with Debian Wheezy, Apache, PHP5.5, and MySQL

1. Debian Wheezy 7.0 x64 [build_essential, vim, curl, git-core]
2. PHP 5.5 - Modules[cli, curl, intl, mcrypt, gd, imagick, ] INI settings[display_errors = On, error_reporting = -1] PECL modules[pecl_http, APC, memcache, varnish, imagick] with composer
3. Apache modules [php, rewrite, expires, vhost_alias, headers] Server Name[virtualserver.dev] Server Aliases[www.virtualserver.dev] Port[80] Document Root[/var/www/]
4. Xdebug
5. XHPROF - http://192.168.56.101/xhprof
6. MySQL root_password=password DB[name=mydb, user=vagrant, pass=vagrant] with phpMyAdmin
