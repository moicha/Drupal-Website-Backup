# Drupal-Website-Backup
Frontend and Database Backups

The avesta.zip files contains the PHP front end.
The CyberForensics-2020-05-03T10-56-28.mysql.gz is the backup of MySql backend

To import this website to your local Acquia Dev Desktop2, perform:
  1. Create a new Drupal site (with new db and codebase).
  2. Create Database and user for site to migrate with phpmyadmin.
  3. Copy sites folder of this back up to the to sites folder of the newly created drupal website.  
  4. Configure settings.php file for server environment.
  5. execute Update.php script

For more details please read the Acquia documentstation here:
https://docs.acquia.com/dev-desktop/start/import/
https://docs.acquia.com/dev-desktop/start/db/
