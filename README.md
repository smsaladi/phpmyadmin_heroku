phpmyadmin_heroku
=================

This is my kludgy way of running phpMyAdmin on Heroku. All you need to do is
customize `config.inc.php` as you would normally to get things running.
Note: The `config.inc.php` is the sample file provided with phpMyAdmin.

If you wish to another display site on the root url and phpmyadmin at
[url]/phpmyadmin, change the `procfile` to the following:
`web: vendor/bin/heroku-php-apache2 /`.

Please register an issue or submit a PR if you think there's a better way of
doing this!

To see this in action, go to https://phpmyadmin-heroku.herokuapp.com which is
built from the `sample_cleardb` branch. That `config.inc.php` has been
configured to bypass login and give complete access. Please be friendly.

