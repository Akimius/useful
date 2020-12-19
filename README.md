# useful
useful things

Build process completed successfully
Installing '/usr/lib/php/20190902/xdebug.so'
install ok: channel://pecl.php.net/xdebug-3.0.1
configuration option "php_ini" is not set to php.ini location
You should add "zend_extension=/usr/lib/php/20190902/xdebug.so" to php.ini


sudo gedit /etc/php/7.4/cli/conf.d/20-xdebug.ini:

[xdebug]
zend_extension="/usr/lib/php/20190902/xdebug.so"
xdebug.mode=debug
xdebug.remote_autostart=1
xdebug.default_enable=1
xdebug.remote_port=9003
xdebug.remote_host=127.0.0.1
xdebug.remote_connect_back=1
xdebug.remote_enable=1
xdebug.idekey=PHPSTORM

