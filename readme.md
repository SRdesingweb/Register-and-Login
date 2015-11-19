<tt>README


1. Clone / Download this project
2. Unzip it, rename it and move it to the folder where you keep your projects
3. Enter from the command line to the project folder and execute: <tt>composer install</tt>.  this is necessary so that all libraries are installed as these do not climb on github.
4. Create the <tt>.env</tt> file and the configure the connection to your database
5. Create the security key with the command: <tt>php artisan key:generate</tt>
6. Run the command: <tt>php artisan migrate:install</tt> , so that the table is believed to migration
7. Run the command <tt>php artisan migrate</tt>
8. Run the command: <tt>php artisan db:seed</tt>, to load test data in the tables
