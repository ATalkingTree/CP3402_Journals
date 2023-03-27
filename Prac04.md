
# Week 5 (Practical 4 Local Development & Deployment)
(https://github.com/CP3402/subject/wiki/Calendar#prac-4---local-development--deployment)

# Learning Activities
This week I learned about WordPress child theme, 

# Resources/Links
LinkedIn course - WordPress: Building Child Themes
https://www.linkedin.com/learning/wordpress-building-child-themes-3/

Help documents for using WP Migrate and Local to start localhost
https://localwp.com/help-docs/getting-started/how-to-import-a-wordpress-site-into-local/
https://deliciousbrains.com/wp-migrate-db-pro/doc/importing-wordpress-local-development-environment/

# Estimated Hours
I spent 3 hours this week (2 hours watching LinkedIn learning and 1 hour learning how to use "Local" and "WP Migrate Lite" to import my live site to my local machine)

# Content Insights
Child themes usually have 2 files, css file for style and php file for function.

CSS: modify styling of the parent theme. The stylesheet of the child will override the parents' one, allowing me to customize the existing parent theme.

PHP: modify the functionality of the parent theme. I can use this to add/modify/remove custom functions.

Having both file separated make it easier to change one without affecting the other, allowing easier change and greater control than having them together in one file. 

# Career/Employability/Learning Insights



# Set Up Local Environment
1. Use WP Migrate Lite plugin (https://wordpress.org/plugins/wp-migrate-db/) to export my current live site to a zip file. In that zip file, it has my wp-content folder (which include all my media uploads, themes and plugins), and my database.
2. Download and install Local (https://localwp.com/). Local is an app use to set up and manage a local development environment on my own computer without using web server or hosting account. 
3. Import my site by adding the zip file generated from step 1 into Local
4. Enjoy my newly created local environment.
