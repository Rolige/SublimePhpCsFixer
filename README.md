# Sublime PHP CS Fixer
This is a plugin for Sublime Text 3 that gives you the option to run
the php-cs-fixer command on any view.

# Features

* It works inside a temporal view (ie: on an inexistent file)
* Fast
* Easy
* Configurable through rules or a config file


# CONFIGURATION

You have to install php-cs-fixer

After installing php-cs-fixer you have to specify the full path to the
executable in the configuration page.

Alternatively you can create a symbolic link to the php-cs-fixer executalbe
(ie: ln -s $HOME/.composer/vendor/bin/php-cs-fixer $HOME/bin/php-cs-fixer)

You can install php-cs-fixer directly with composer by running:

    composer global require friendsofphp/php-cs-fixer

Or for more information check https://github.com/FriendsOfPHP/PHP-CS-Fixer

I've checked this on Linux, but I cannot check it on windows nor osx,
I'll thank you if someone tells me if it's working on these platforms
and give me some details on how to configure i


# Acknowledgements

I would like to thank to sensiolab and contributors for their awesome package
it works flawlessly. All the work here belongs to them.

Check them at:
    - https://github.com/FriendsOfPHP/PHP-CS-Fixer
    - http://cs.sensiolabs.org/

I'd also learned some of the sublime package structure from:
    - https://github.com/Ennosuke/PHP-Codebeautifier