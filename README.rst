===============
PHP BDD Toolset
===============

Provides an easy installation of Behat, Mink and PHPSpec for the best BDD toolset available for PHP.

Installation:

    mkdir -p /usr/share/toolsets
    cd /usr/share/toolsets
    git clone https://github.com/andho/php-bdd-toolset.git
    cd php-bdd-toolset
    php composer.phar install
    echo 'export PATH=$PATH:/usr/share/toolsets/php-bdd-toolset/vendor/bin' >> ~/.bashrc

Usage:
    
Now you can run phpspec or behat anywhere from the command line, just as if you had installed it using PEAR.
