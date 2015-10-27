# Restfull web application of restaurants and corresponding menus

This is one of the web projects in Full Stack Web Developer Nanodegree in Udacity.

In this project, I wrote sql scheme, built an web server using flask framwork of python and using SQLalchemy API to connect the sqlite database. I made a Restfull web application which can provide HTTP related CRUD methods handling a list of restaurant and its menus. JSON APIs are also provided for data query. Then I implement third pary OAuth authentication for restaurants and menus management. 

- Skills: Google+ API, Facebook SDK, Restfull API SQLalchemy API, Sqlite Database, Python, Javascript, JQuery, Ajax, HTML, CSS, Json

Features: <br/>
1. Using Flask ( a light Python web framework).<br/>
2. Using OAuth 2.0 to access Google APIs and Facebook API using google or facebook account.<br/>
3. Using RESRfull APIs, like Post and Get.<br/>
4. Providing JSON APIs, which you can exploit to get the information you want.<br/>

1. Run database_setup.py to create restaurantmenu.db
2. Run project.py to connect the sqlite database and webserver
3. Go to http://localhost:5000/ and you will see the page as below

![image](https://raw.githubusercontent.com/leiyudongyu/images/master/1.jpg)

You can choose each restaurant and find their menus as below:

![image](https://raw.githubusercontent.com/leiyudongyu/images/master/2.jpg)

Because you are not login, so you can not create or delete or edit restaurants and menus, and there are no such buttons showing on the page.

If you are the user, you can click log in options on the right corner of the page, then you can choose using Google+ or Facebook to login.

![image](https://raw.githubusercontent.com/leiyudongyu/images/master/3.jpg)

![image](https://raw.githubusercontent.com/leiyudongyu/images/master/4.jpg)

Then you can see you are now log in as (your name) and a Add restaurant button shows:

![image](https://raw.githubusercontent.com/leiyudongyu/images/master/5.jpg)

You can click it and add Restaurant name, then a new restaurant cooresponding to your user_id will be create, and you can manipulate its menus by click the restaurant's name:

![image](https://raw.githubusercontent.com/leiyudongyu/images/master/6.jpg)

![image](https://raw.githubusercontent.com/leiyudongyu/images/master/7.jpg)

Comparing with non-login page, you can see there are more buttons on the page which can let you manipulate your restaurant and its menus.

Changing restaurant's name:

![image](https://github.com/leiyudongyu/images/blob/master/8.jpg)

Adding menu items:

![image](https://github.com/leiyudongyu/images/blob/master/9.jpg)

Delete restaurant:

![image](https://github.com/leiyudongyu/images/blob/master/10.jpg)

For each menu, you can edit, delete too:

Edit menu:

![image](https://github.com/leiyudongyu/images/blob/master/11.jpg)

Delete menu:

![image](https://github.com/leiyudongyu/images/blob/master/12.jpg)

If you want to log out, you can click the log out button on the right-top of the page, then you can see you have been log out:

![image](https://github.com/leiyudongyu/images/blob/master/13.jpg)
