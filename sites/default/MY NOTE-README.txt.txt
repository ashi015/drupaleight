
##For installing Drupal8 if you have both code and DB###

- Copy example.settings.local.php to default and rename to settings.local.php and Add data base details like below
    $databases['default']['default'] = array (
      'database' => 'acquiaDrupaleight',
      'username' => 'root',
      'password' => 'root',
      'prefix' => '',
      'host' => 'localhost',
      'port' => '3306',
      'namespace' => 'Drupal\\Core\\Database\\Driver\\mysql',
      'driver' => 'mysql',
    );
- Ensure ' $settings['hash_salt'] = 'sdgfsdfgsdfgdfgtrghgfhdfhdhfgh'; ' present in settings.php or settings.local.php