# WPLite (now part of SlickStack)

WordPress boilerplate focused on speed, security, and lightweight code that includes several Must Use plugins and also supports Composer (Packagist).

* [Boilerplate Homepage](https://wplite.org)
* [**Become A LittleBizzy.com Member Today!**](https://www.littlebizzy.com/members)

### Defined Constants

    /* WPLite Functions */
    define('DELETE_EXPIRED_TRANSIENTS', true);
    define('DELETE_EXPIRED_TRANSIENTS_HOURS', '6');
    define('DELETE_EXPIRED_TRANSIENTS_MAX_EXECUTION_TIME', '10');
    define('DELETE_EXPIRED_TRANSIENTS_MAX_BATCH_RECORDS', '50');
    define('DISABLE_ADMIN_AJAX', false);
    define('DISABLE_CART_FRAGMENTS', true);
    define('DISABLE_EMBEDS', true);
    define('DISABLE_EMBEDS_ALLOWED_SOURCES', 'none');
    define('DISABLE_EMOJIS', true);
    define('DISABLE_GUTENBERG', true);
    define('DISABLE_JQUERY_MIGRATE', true);
    define('DISABLE_POST_VIA_EMAIL', true);
    define('DISABLE_WOOCOMMERCE_STATUS', false);
    define('DISABLE_WOOCOMMERCE_STYLES', false);
    define('DISABLE_WOOCOMMERCE_STYLES_NAMES', 'select2');
    define('DISABLE_WOOCOMMERCE_STYLES_PREFIXES', 'woocommerce,wc');
    define('DISABLE_XML_RPC', true);
    define('HEADER_CLEANUP', true);
    define('INDEX_AUTOLOAD', true);
    define('INDEX_AUTOLOAD_REGENERATE', false);
    define('INLINE_STYLES', false);
    define('MINIFY_HTML', true);
    define('MINIFY_HTML_INLINE_STYLES', true);
    define('MINIFY_HTML_INLINE_STYLES_COMMENTS', true);
    define('MINIFY_HTML_REMOVE_COMMENTS', true);
    define('MINIFY_HTML_REMOVE_CONDITIONALS', true);
    define('MINIFY_HTML_REMOVE_EXTRA_SPACING', true);
    define('MINIFY_HTML_REMOVE_HTML5_SELF_CLOSING', false);
    define('MINIFY_HTML_REMOVE_LINE_BREAKS', true);
    define('MINIFY_HTML_INLINE_SCRIPTS', false);
    define('MINIFY_HTML_INLINE_SCRIPTS_COMMENTS', false);
    define('MINIFY_HTML_UTF8_SUPPORT', true);
    define('REMOVE_QUERY_STRINGS', true);
    define('REMOVE_QUERY_STRINGS_ARGS', 'v,ver,version');

### Support Issues

Please do not submit Pull Requests. Instead, kindly create a new Issue with relevant information if you are an experienced developer, otherwise you may become a [**LittleBizzy.com Member**](https://www.littlebizzy.com/members) if your company requires official support.

----

Place inside `/var/www/html/` when installing via [SlickStack](https://slickstack.io) on a LEMP (Nginx) server:

    composer.json
    /wp-admin/
        ...
    /wp-content/
        index.php
        /mu-plugins/
            /cf-littlebizzy/
            /delete-expired-transients-littlebizzy/
            /disable-admin-ajax-littlebizzy/
            /disable-customizer-littlebizzy/
            /disable-embeds-littlebizzy/
            /disable-emojis-littlebizzy/
            /disable-empty-trash-littlebizzy/
            /disable-image-compression-littlebizzy/
            /disable-post-via-email-littlebizzy/
            /disable-xml-rpc-littlebizzy/
            /error-log-monitor-littlebizzy/
            /force-strong-hashing-littlebizzy/
            /header-cleanup-littlebizzy/
            /index-autoload-littlebizzy/
            /nginx-cache-littlebizzy/
            /remove-query-strings-littlebizzy/
            /server-status-littlebizzy/
            /virtual-robotstxt-littlebizzy/
            index.php
        /plugins/
            index.php
        /themes/
            /bones/
            /sage/
            /starter-littlebizzy/
            /storefront/
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
    
    
 ## copied from the wplite.org homepage to here 
 
 http://archive.is/wplite.org
 
 # Themes
 
Because wplite includes Repo Search in the mu-plugins, users can use both the traditional WordPress search tool to discover new themes but also search thousands of themes across GitHub that do not show up in the centralized Automattic-controlled theme directory on WordPress.org.

Repo Search is based partly on WPGIT and the StaticGen codebase.

https://github.com/onigetoc/wpgit
https://github.com/netlify/staticgen

*Coming soon*

# Plugins

Because wplite includes Repo Search in the mu-plugins, users can use both the traditional WordPress search tool to discover new plugins but also search thousands of plugins across GitHub that do not show up in the centralized Automattic-controlled plugin directory on WordPress.org.

Repo Search is based partly on WPGIT and the StaticGen codebase.

https://github.com/onigetoc/wpgit
https://github.com/netlify/staticgen

*Coming soon*

# Contribute

Because wplite is largely made up of mu-plugins released by LittleBizzy, contributing to the project can be done easily by submitting a new “Issue” on any one of these GitHub repos.

https://github.com/littlebizzy

In this way, all discussions are public, and anyone with a GitHub account can participate.

Watch this space for more opportunities coming soon.

# Hosting

Anywhere that you can host WordPress, you should also be able to host wplite. However, certain web hosting companies try to provide an extra bit of support to wplite installations by way of documentation, links, or otherwise, some of which we have listed below:

(pending submissions)
 

Does your hosting company support wplite specifically? Let us know.

https://github.com/littlebizzy/wplite/issues/new

# Download

Your team can easily substitute wplite into your normal WordPress workflow. Our public repo is regularly updated and always bundles the latest version of WordPress, including all security patches.

Use the download link below to grab the latest ZIP package:

Download wplite (latest ZIP package)

https://wplite.org/latest.zip

Download wplite mirror (latest ZIP package)

https://github.com/littlebizzy/wplite/archive/master.zip

Alternatively, you may use the wpl.fyi shortcut in your various scripts as below:

sudo wget wpl.fyi




