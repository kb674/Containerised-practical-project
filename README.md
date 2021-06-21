# Containerised practical project
Configuration file to run my practical project app using docker-compose.

## Export environment variables

* export ``MYSQL_DATABASE=( enter a database )``

* export ``MYSQL_ROOT_PASSWORD=( enter a password )``
* export ``DATABASE_URI=mysql+pymysql://root:( password )@mysql/( database )``

## To deploy
*  ``docker-compose up -d`` to run

* ``docker-compose down --rm all`` to cleanup.
