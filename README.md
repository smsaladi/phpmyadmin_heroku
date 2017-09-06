phpmyadmin_heroku
=================

This is my kludgy way of running phpMyAdmin on Heroku. All you need to do is
customize `config.inc.php` as you would normally to get things running.
Note: The `config.inc.php` has been modified to pull Heroku config variables;
for a production system, you will probably want to change the authentication
parameters.

Please register an issue or submit a PR if you think there's a better way of
doing this!

To see this in action, go to https://phpmyadmin-heroku.herokuapp.com.
`config.inc.php` is configured to bypass login and give complete access.
Please be friendly.

