# Base Laravel 5.1.* Distribution

This is a base Laravel 5.1.* distribution to use for making Laravel apps with 5.1.* preferred distribution.

Jessica's configuration:

* VerifyCsrfToken is commented out in Kernel.php
* Password min length is 4 (instead of 6) in AuthController.php
* $redirectTo added to AuthController.php
* Bootstrap added to composer.json
* Uuid added to composer.json and app.php