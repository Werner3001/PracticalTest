1. Update config/database.php to link with your local 
database.

IN THE CLI IN THE BASE DIRECTORY, DO THE FOLLOWING : 
2. run the command: "php artisan migrate"

3. run the command: "php artisan make:filament-user", 
(
follow the prompt in the CLI to create a admin user, 
in testing I used:
Name: admin
Email: admin@admin.com
Password: admin 
)

4. run the command: "php artisan shield:install" 
(Will assign the admin user a role).

5. run the command: "php artisan serve"

6. The app should now be running.