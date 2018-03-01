#### WordPress boilerplate focused on speed, security, and lightweight code that includes several Must Use plugins and also supports Composer (Packagist).

[![GitHub stars](https://img.shields.io/github/stars/littlebizzy/wplite.svg?style=social&logo=github&label=Star)](https://github.com/littlebizzy/wplite/stargazers) [![GitHub forks](https://img.shields.io/github/forks/littlebizzy/wplite.svg?style=social&logo=github&label=Fork)](https://github.com/littlebizzy/wplite/fork)

Designed to be placed in `/var/www/html/` when installed via [slickstack](https://slickstack.io):

    composer.json
    index.php
    wp-config.php
    /wp-content/mu-plugins/
    /wp-content/mu-plugins/cf-littlebizzy/
    /wp-content/mu-plugins/delete-expired-transients-littlebizzy/
    /wp-content/mu-plugins/disable-embeds-littlebizzy/
    /wp-content/mu-plugins/disable-emojis-littlebizzy/
    /wp-content/mu-plugins/disable-empty-trash-littlebizzy/
    /wp-content/mu-plugins/disable-image-compression-littlebizzy/
    /wp-content/mu-plugins/disable-xml-rpc-littlebizzy/
    /wp-content/mu-plugins/error-log-monitor-littlebizzy/
    /wp-content/mu-plugins/force-strong-hashing-littlebizzy/
    /wp-content/mu-plugins/header-cleanup-littlebizzy/
    /wp-content/mu-plugins/nginx-cache-littlebizzy/
    /wp-content/mu-plugins/remove-query-strings-littlebizzy/
    /wp-content/mu-plugins/server-status-littlebizzy/
    /wp-content/mu-plugins/virtual-robotstxt-littlebizzy/
    /wp-content/plugins/
    /wp-content/themes/
    /wp-content/uploads/

Defined constants supported by included Must Use plugins:

    define('REMOVE_QUERY_STRING_ARGS', 'v,ver,version');
    define('DELETE_EXPIRED_TRANSIENTS_HOURS', '24');
    define('DELETE_EXPIRED_TRANSIENTS_MAX_EXECUTION_TIME', '60');
    define('DELETE_EXPIRED_TRANSIENTS_MAX_BATCH_RECORDS', '500');

Made with ❤ by [LittleBizzy](https://www.littlebizzy.com) | Licensed under [GPLv3](https://www.gnu.org/licenses/gpl-3.0)
