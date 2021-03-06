RestaurantReviews
=================

The Problem
--------------
Truefit is in the midst of building a mobile application that will let restaurant patrons rate the restaurant in which they are eating. As part of the build, we need to develop an API that will accept and store the ratings and other sundry data. 

For this project, we would like you to build this api. Feel free to add your own twists and ideas to what type of data we should collect and return, but at a minimum your API should be able to:

1. Get a list of restaurants by city
2. Post a restaurant that is not in the database
3. Post a review for a restaurant
4. Get of a list of reviews by user
5. Delete a review

The Fine Print
--------------
Please use whatever technology and techniques you feel are applicable to solve the problem. We suggest that you approach this exercise as if this code was part of a larger system. The end result should be representative of your abilities and style.

Please fork this repository. When you have completed your solution, please issue a pull request to notify us that you are ready.

Have fun.
=========================================================================================================

This application was developed and tested with the following configuration

1- Apache v2.4.9 (rewrite_module enabled)

2- PHP 5.5.12

3- MySQL 5.6.17;

4- Composer Dependency Management for PHP (getcomposer.org)

5- Slim Framework (www.slimframework.com/)

6- idiorm (idiorm.readthedocs.org)

Once apache virtual directory and db are setup, type any of the following paths
API Calls:
----------
GET - [domain]/restaurants/city/:id      (list of restaurants by city)

POST - [domain]/restaurants/             (add restaurant)

GET - [domain]/restaurants/:id           (details of a restaurant)

GET - [domain]/reviews/user/:id          (reviews by user)

POST - [domain]/reviews/                 (add review)

DELETE - [domain]/reviews/               (delete review)

Restaurant Tests:
----------------
[domain]/test/RestaurantTests/add

[domain]/test/RestaurantTests/details 
