# Bookstore
#### Authored by Dylan Stackhouse, 4/21/17.

## Description
A Bookstore website which features reviews and information on the books carried.

## Setup/Installation Requirements
_To view and use this application:_
* It is necessary to download and install MAMP to use this application
    * Go to [mamp.info] (https://www.mamp.info/en/downloads/) to download MAMP for free. Set your Apache port to 8888 and mySQL port to 8889, and launch the server from the project directory.
* Clone this git repository: [Bookstore](https://github.com/DylanCStack/bookstore.git)
* Inside of the **_db-backup_** folder, unzip the **_bookstore.sql.zip_** file
* Open MAMP (or equivalent) and click on preferences/ports.
    * Make sure that the Apache port number is set to 8888 and the MySQL port number is set to 8889
    * Click start servers.
* Type **_localhost:8888/phpmyadmin_** into your web browser
    * Click the _Import_ tab on the nav bar
    * Click _Choose File_ and navigate to the unzipped **_bookstore.sql_**
    * click _GO_
* Type **_localhost:8888_** into your web browser
* The application will load and be ready to use!

## Technologies Used
* Drupal
* mySQL
* HTML
* CSS
* JavaScript

## User Stories
As a user, can view books and book reviews.
As a authenticated user, I want to see special deals avaliable to me.
As a reviewer, I can create a book review which will appear on the site's sidebar.
As a reviewer, I can delete or edit my reviews.


This software is licensed under the GPL license

_If you have any questions or comments about this program, you can contact me [Stackhouse.Dylan@gmail.com](mailto:Stackhouse.Dylan@gmail.com)._

Copyright (c) 2017 Dylan Stackhouse
