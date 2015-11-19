
1. Clone / Download this project
2. Unzip it, rename it and move it to the folder where you keep your projects
3. Enter from the command line to the project folder and execute: composer install, this is necessary so that all libraries are installed as these do not climb on github.
4. Create the .env file and the configure the connection to your database
5. Create the security key with the command: php artisan key: generate
6. Run the command: php artisan migrate: install, so that the table is believed to migration
7. Run the command php artisan migrate
8. Run the command: php artisan db: seed, to load test data in the tables
