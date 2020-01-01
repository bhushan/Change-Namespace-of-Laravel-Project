# Changing Laravel 6 namespace

First we create the command with

```bash
php artisan make:command AppName
```

Then we replace the content created in the file app/Console/Commands/AppName.php with the content of the gist.

and then use it in the usual way, changing Enlight for the name of your application.

```bash
php artisan app:name Enlight
```
