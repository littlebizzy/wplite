#### WordPress boilerplate focused on speed, security, and lightweight code that includes several Must Use plugins and also supports Composer (Packagist).

[![GitHub stars](https://img.shields.io/github/stars/littlebizzy/wplite.svg?style=social&logo=github&label=Star)](https://github.com/littlebizzy/wplite/stargazers) [![GitHub forks](https://img.shields.io/github/forks/littlebizzy/wplite.svg?style=social&logo=github&label=Fork)](https://github.com/littlebizzy/wplite/fork)

Designed to be placed in `/var/www/html/` when installed via [slickstack](https://slickstack.io):

    composer.json
    index.php // wpcore
    wp-config.php // wpcore
    /wp-content/mu-plugins/ // wpcore
    ```diff
    /wp-content/mu-plugins/cf-littlebizzy/
    ```
    /wp-content/mu-plugins/delete-expired-transients-littlebizzy/ // wplite
    /wp-content/mu-plugins/disable-embeds-littlebizzy/ // wplite
    /wp-content/mu-plugins/disable-emojis-littlebizzy/ // wplite
    /wp-content/mu-plugins/disable-empty-trash-littlebizzy/ // wplite
    /wp-content/mu-plugins/disable-image-compression-littlebizzy/ // wplite
    /wp-content/mu-plugins/disable-xml-rpc-littlebizzy/ // wplite
    /wp-content/mu-plugins/error-log-monitor-littlebizzy/ // wplite
    /wp-content/mu-plugins/force-strong-hashing-littlebizzy/ // wplite
    /wp-content/mu-plugins/header-cleanup-littlebizzy/ // wplite
    /wp-content/mu-plugins/nginx-cache-littlebizzy/ // wplite
    /wp-content/mu-plugins/remove-query-strings-littlebizzy/ // wplite
    /wp-content/mu-plugins/server-status-littlebizzy/ // wplite
    /wp-content/mu-plugins/virtual-robotstxt-littlebizzy/ // wplite
    /wp-content/plugins/ // wplite
    /wp-content/themes/ // wpcore
    /wp-content/uploads/ // wpcore

Defined constants supported by included Must Use plugins:

    define('REMOVE_QUERY_STRING_ARGS', 'v,ver,version');
    define('DELETE_EXPIRED_TRANSIENTS_HOURS', '24');
    define('DELETE_EXPIRED_TRANSIENTS_MAX_EXECUTION_TIME', '60');
    define('DELETE_EXPIRED_TRANSIENTS_MAX_BATCH_RECORDS', '500');

Made with ❤ by [LittleBizzy](https://www.littlebizzy.com) | Licensed under [GPLv3](https://www.gnu.org/licenses/gpl-3.0)
