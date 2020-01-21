# simple-url-shortener
 
A Simple PHP Script for URL shortening. This script is Open Source, please feel free to contribute.

Installation:

Create a database with a user and run this sql

CREATE TABLE IF NOT EXISTS url_shorten(idint(11) NOT NULL AUTO_INCREMENT PRIMARY KEY,urltinytext NOT NULL,short_codevarchar(50) NOT NULL,hitsint(11) NOT NULL,added_datetimestamp NULL DEFAULT CURRENT_TIMESTAMP ) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=latin1;

Copy the index.php file to your domain or subdomain root directory and change the db name, username and password.

You can add additional protection to make the page private.
