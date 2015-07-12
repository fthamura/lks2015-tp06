This vagrant config file only work for ubuntu trusty (14.04) 64bit

Add ubuntu trusty vagrant box with command: vagrant box add ubuntu/trusty64

1. Install laravel5 via composer or manually
2. Copy VagrantFile and provision folder to your laravel workspace

Including Software:

1. LEMP (Nginx + PHP-FPM + MariaDB)
2. Postfix and Dovecot (Mail Server)

Vagrant will automatically generate your laravel config.
Username and password of your database and mail can be found at .vagrant/user-pass.

All services use same username and password.

Thank you