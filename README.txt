I was able to achieve the following due to some research and examples because it's my first time using Drupal. I actually did not get enough material for connecting to drupal database but still found some cool features like webforms, blocks, connecting to live feeds, integrating with other web design languages like css, html, getting some already created function on drupal.org and reusability of functions. I believe these features made Drupal one of the best. 

I was able to create a simple drupal website which includes
the electric boogaloo form registration. it takes the name, 
email and student id of students. These values can be stored 
and viewed locally on the website. 
I manually created a database through the Acquia dev desktop
I had a little bit of challenge storing the values into the
database that was created. I am assuming my implementation 
is not correctly handled. I took these steps for the database.
1. I created a local database with the necessary fields
2. I created an Electric_boogaloo module. I learnt that this is necessary to store the student form and it is required for the webform.
3. I created the electric_boogaloo.install, .info and .module file. I wrote some functions to get into the database from the .module file.
4. I did not get any error after connecting the files to the webform but for some reasons, it is not connecting to the database that was manually created but can be stored and viewed locally within the webpage.

I was able to use drush as well, which his the Drupal command line. I viewed the commands 
In drush and use some basic commands like drush clear-cache and shortcuts like drush cc all to clear caches of Drupal site, drush sql-connect to connect to database