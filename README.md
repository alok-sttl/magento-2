magento-2
=========
INSTALLTAION (Using GIThub Poweshell)
--------------
1. Clone git repo magento2 (git clone https://[your github.com user name]:[password]@github.com/magento/magento2.git OR using ssh- git clone git@github.com:magento/magento2.git)
2. Download composer.phar and put in magento2 (php -r "readfile('https://getcomposer.org/installer');" | php OR WGET https://getcomposer.org/installer)
3. Run php composer.phar install
4. Copy composer.phar and put in magento2/setup
5. Run php composer.phar install
6. Run http://www.domain.com/magento2/setup in browser
7. Enter details and continue

Deploy CSS and JS
------------------
php -f ./magento2/dev/tools/Magento/Tools/View/deploy.php

Reinstalling the Magento 2 software
--------------
1. cd [your Magento install dir]
2. git pull
3. composer install
4. cd setup
5. composer install