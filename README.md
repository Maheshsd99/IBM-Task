# IBM-Task
# Complete the below process

Follow the below steps to Run the Drupal
--------------------------------------------
- If you dont have xampp then download the xampp first by using below URL
 https://www.apachefriends.org/index.html
 
- Once xampp downloaded then install the xampp by clicking on downloaded file.
  and Follow the onscreen instructiona at the time of installation.
 
- once xampp installed then start you server (apache and mysql)
  Go to Location - C:\xampp
  then find out xampp-control in that xampp folder and click on xampp-control then start apache and mysql server.
 
- Once the above process is done then Download the drupal-9.0.7 and drupal9.sql files from the given repo.

- Put this drupal-9.0.7 in your XAMPP folder - (Location - C:/xampp/htdocs/)

- Open localhost in your browser and import the downloaded database sql file (drupal9.sql) - http://localhost/phpmyadmin/

- Open your browser and put the below URL in browser - http://localhost/drupal-9.0.7

- Once site is working properly then copy the below URL and paste it into your browser   
  http://localhost/drupal-9.0.7/user/login
  
  Username - IBM Drupal
  
  Password - admin#123
  
  login with the given credetials
  
- Run the below JSON API to find the task output
  
  http://localhost/drupal-9.0.7/api/menunavigation?_format=json
  
  Response
   
  [{"title":"Menu Navigation","view_node":"\/drupal-9.0.7\/node\/1","field_menu_description":"This is home page menu","field_menu_icon":"\/drupal-9.0.7\/sites\/default\/files\/2020-10\/Menu_icon_0.png","field_menu_item_name":"Home Page Menu","field_menu_link_url":"\u003Ca href=\u0022http:\/\/localhost\/drupal-9.0.7\/\u0022\u003Ehttp:\/\/localhost\/drupal-9.0.7\/\u003C\/a\u003E","field_parent_menu":"Home"}]
  