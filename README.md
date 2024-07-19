# PGLife
The website is called PGLife. This project keeping in mind how challenging it is for the students
to search for good accommodation when they join college/university. I guess we all might also
have faced the challenge of finding good accommodation when you joined college.

So, this web application helps the students to get PGs in their desired cities with wonderful
amenities and this web application have fully functional features which meets the
requirements of today’s generation.

The very first thing is we need to design the web interface with the help of HTML, CSS,
Bootstrap. We need to create an index page which works as index for all the pages, then we
need to create login and signup page which slides on the index page when we click on the
login/signup button, we also need to create property list page which shows the properties of
the selected city, followed with property list page, we also need to create property details page
which gives the detailed structure of particular property and at last we need to design
dashboard page. This page will be accessible only if the user logs in. We will check if the user
logged in or not with the help of PHP sessions.

After this, JavaScript takes the role to add the functionalities of hover and On Click event
handlers.We also need to create database, for this, we are using PhpMyAdmin of XAMPP control panel.
We need 7 tables to store the varies of information which we will get from the user.
Users - in users table we will store the details of the user who had signed up in the PGLife
website.

Cities                     - in this tables will store the details of the cities where the properties are located. 
Properties                 - in this table we will store the detail information of the property which includes the details of property description, rent details 
                             and address, etc.,
User_interested_properties - In this table, we will store the properties which were plotted as interested by the user along with the details of the user which 
                             marked it as interested.
Testimonials               - In this table, we will store the reviews on the property given by the customer.
Amenities                  - In this table, we will store all the amenities provided by all the properties like (WIFI, geyser, food, parking) facilities provided 
                             by the property owner.
