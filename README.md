# phpfarm
For Php Version Changer
phpfarm is a set of scripts to install a dozen of PHP versions in parallel on a single system. It also installs the pear and pyrus installers and creates a local Pyrus installation for each PHP version as well.

This tool was primarily developed for PEAR's continuous integration machine.

The PHP source packages are fetched from http://museum.php.net/ (which is not always up-to-date), the official php.net download pages and the pre-release channels.

The Pyrus PHAR archive is fetched from http://pear2.php.net/pyrus.phar (which always refers the latest version).

If a file cannot be found, try to fetch it manually and put it into src/bzips/.

Setup
Check out phpfarm from git:
