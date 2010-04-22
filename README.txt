This file is for you to describe the nerdherd application. Typically
you would include information such as the information below:

Installation and Setup
======================

Install ``nerdherd`` using easy_install::

    easy_install nerdherd

Make a config file as follows::

    paster make-config nerdherd config.ini

Tweak the config file as appropriate and then setup the application::

    paster setup-app config.ini

Then you are ready to go.




------------------------
real install instructions

virtualenv --no-site-packages pylons
cd pylons
source bin/activate
pip install -r REQUIREMENTS
git clone git://github.com/askedrelic/nerdherd-pylons.git
paster serve --reload development.ini
