#### WordPress boilerplate focused on speed, security, and lightweight code that includes several Must Use plugins and also supports Composer (Packagist).

[![Github all releases](https://img.shields.io/github/downloads/littlebizzy/wplite/total.svg)](https://github.com/littlebizzy/wplite/archive/master.zip) [![GitHub stars](https://img.shields.io/github/stars/littlebizzy/wplite.svg?style=social&logo=github&label=Star)](https://github.com/littlebizzy/wplite/stargazers) [![GitHub forks](https://img.shields.io/github/forks/littlebizzy/wplite.svg?style=social&logo=github&label=Fork)](https://github.com/littlebizzy/wplite/fork)

Place inside `/var/www/html/` when installing via [SlickStack](https://slickstack.io) on a LEMP (Nginx) server:

    composer.json
    /wp-admin/
        ...
    /wp-content/
        index.php
        /mu-plugins/
            cf-littlebizzy/
            delete-expired-transients-littlebizzy/
            disable-embeds-littlebizzy/
            disable-emojis-littlebizzy/
            disable-empty-trash-littlebizzy/
            disable-image-compression-littlebizzy/
            disable-xml-rpc-littlebizzy/
            error-log-monitor-littlebizzy/
            force-strong-hashing-littlebizzy/
            header-cleanup-littlebizzy/
            nginx-cache-littlebizzy/
            remove-query-strings-littlebizzy/
            server-status-littlebizzy/
            virtual-robotstxt-littlebizzy/
            index.php
        /plugins/
            index.php
        /themes/
            /bones/
            /sage/
            /starter-littlebizzy/
            /underscores/
            index.php
    /wp-includes/
        ...
    index.php
    license.txt
    wp-activate.php
    wp-blog-header.php
    wp-comments-post.php
    wp-config-sample.php
    wp-cron.php
    wp-links-opml.php
    wp-load.php
    wp-login.php
    wp-settings.php
    wp-signup.php

List of defined constants supported by wplite:

    // Disable Nag Notices
    define('DISABLE_NAG_NOTICES', true);
    
    // CloudFlare
    define('CLOUDFLARE_API_KEY', '123456789');
    define('CLOUDFLARE_API_EMAIL', 'user@example.com');
    
    // Delete Expired Transients
    define('DELETE_EXPIRED_TRANSIENTS_HOURS', '6');
    define('DELETE_EXPIRED_TRANSIENTS_MAX_EXECUTION_TIME', '10');
    define('DELETE_EXPIRED_TRANSIENTS_MAX_BATCH_RECORDS', '50');
    
    // Force Strong Hashing
    define('FORCE_STRONG_HASHING_ALGO', 'bcrypt | argon2');
    
    // Remove Query Strings
    define('REMOVE_QUERY_STRINGS_ARGS', 'v,ver,version');
    
    // Server Status
    define('SVRSTS_DISPLAY', 'grid | widefat');
    
    // Virtual Robots.txt
    define('VIRTUAL_ROBOTSTXT_PRESET', 'default | noarchive');

❤ from [LittleBizzy](https://www.littlebizzy.com) | License: [GPLv3](https://www.gnu.org/licenses/gpl-3.0)
