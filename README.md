# mult_php
Multiplas versões PHP

install mult versions PHP

sudo add-apt-repository ppa:ondrej/php
sudo apt-get update
sudo apt-get install php8.0 php8.0-fpm php8.0-xml php8.0-mysql php8.0-gd

Configurations in file .sh

Enter the choice number mentioned besides the desired PHP version

sudo update-alternatives -set php /usr/bin/php7.4

For Apache web server, the a2enmod and a2dismod scripts can be used for enabling and disabling the PHP modules.Disable all the previously enabled PHP modules

sudo a2dismod php5.6
sudo a2dismod php7.0
sudo a2dismod php7.1


copy file .sh to /usr/bin/usephp.8.0

permission: sudo chmod +x /usr/bin/usephp.8.0

command line: usephp8.0

