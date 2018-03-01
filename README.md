#### WordPress boilerplate focused on speed, security, and lightweight code that includes several Must Use plugins and also supports Composer (Packagist).

[![GitHub stars](https://img.shields.io/github/stars/littlebizzy/wplite.svg?style=social&logo=github&label=Star)](https://github.com/littlebizzy/wplite/stargazers) [![GitHub forks](https://img.shields.io/github/forks/littlebizzy/wplite.svg?style=social&logo=github&label=Fork)](https://github.com/littlebizzy/wplite/fork)

Designed to be used in conjuction with SlickStack:

    /var/www/html/composer.json
    /var/www/html/index.php
    /var/www/html/wp-config.php
    /var/www/html/wp-content/mu-plugins/
    /var/www/html/wp-content/mu-plugins/cf-littlebizzy/
    /var/www/html/wp-content/mu-plugins/delete-expired-transients-littlebizzy/
    /var/www/html/wp-content/mu-plugins/disable-embeds-littlebizzy/
    /var/www/html/wp-content/mu-plugins/disable-emojis-littlebizzy/
    /var/www/html/wp-content/mu-plugins/disable-empty-trash-littlebizzy/
    /var/www/html/wp-content/mu-plugins/disable-image-compression-littlebizzy/
    /var/www/html/wp-content/mu-plugins/disable-xml-rpc-littlebizzy/
    /var/www/html/wp-content/mu-plugins/error-log-monitor-littlebizzy/
    /var/www/html/wp-content/mu-plugins/force-strong-hashing-littlebizzy/
    /var/www/html/wp-content/mu-plugins/header-cleanup-littlebizzy/
    /var/www/html/wp-content/mu-plugins/nginx-cache-littlebizzy/
    /var/www/html/wp-content/mu-plugins/remove-query-strings-littlebizzy/
    /var/www/html/wp-content/mu-plugins/server-status-littlebizzy/
    /var/www/html/wp-content/mu-plugins/virtual-robotstxt-littlebizzy/
    /var/www/html/wp-content/plugins/
    /var/www/html/wp-content/themes/
    /var/www/html/wp-content/uploads/

Defined constants supported by included Must Use plugins:

    define('REMOVE_QUERY_STRING_ARGS', 'v,ver,version');
    define('DELETE_EXPIRED_TRANSIENTS_HOURS', '24');
    define('DELETE_EXPIRED_TRANSIENTS_MAX_EXECUTION_TIME', '60');
    define('DELETE_EXPIRED_TRANSIENTS_MAX_BATCH_RECORDS', '500');

Made with ❤ by [LittleBizzy](https://www.littlebizzy.com) | Licensed under [GPLv3](https://www.gnu.org/licenses/gpl-3.0)
