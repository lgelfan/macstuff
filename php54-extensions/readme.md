put .so extensions into mac php extensions directory, current (Mavericks) is for PHP 5.4:

/usr/lib/php/extensions/no-debug-non-zts-20100525

check that your php build number is the same.

then add the phpini updates to your /etc/php.ini file, see the one here for example if you don't have one. the updates can go pretty much anywhere, but i would put them at the end of the extensions section.