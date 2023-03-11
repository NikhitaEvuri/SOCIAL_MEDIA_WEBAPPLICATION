# SOCIAL_MEDIA_WEBAPPLICATION


This web application is basically like similar to social media app

In this web application. we are using MERN stack 

These are the web technologies used in our project
(Mongo DB database,
For Frontend we use React js
and for Backend we use Node js, Express js)

In this web application first requires Authentication which contains Register and Login views.

Home page contains Register and Login buttons.

If we click on Register, Register web page view will be visible which contains form 
(details such as FirstName,
      LastName,
      Email,
      Password,
      Picture,
      Location,
      Occupation )
      
New user should register by filling all the details. So, that user get registered to our website.

Remaining details except password are directly stored in database. Password is Bcrypted and stored in database.

Already registered user can login to our website by using Login view.

If we click on Login, Login web page view will be visible which contains form 
(details such as Email,
      Password )
      
After entering the details. Those details are checked with the database if they are matched we will be entered into Home view.
Or else it shows error message as Incorrect Email or Password according to match of the database.

Home views shows all the posts that exists.

Home view basically contains Navbar which contains search feature where user can search by username, location, occupation

According to that specific search like If I search for tadepalligudem so, all the user posts of tadeplligudem will be visible. and so. on.

NavBar also contains for Theme change (like DARK mode or LIGHT mode ) according to that background color of the whole application got changed..

NavBar also contains Logout feature. (By clicking that user can logout of their account in our website ).

NavBar also contains Profile feature. By clicking on this option Profile view will be opened which contains 
    ( Details that we collected from user during registering of a user. 
    Where user can edit their credentials, and also change password and edit their Profile Picture.
    So, database gets updated with the updated credentails. )
    
Post contains the username of the post creator and also location and also likes and comments
(Any registered user can like and comment the post)

If we click on a POST it will be opened in a Bigger view.

We can connect with our friends by using this web application. We have Friends List in this application. 
Where we can add friends to friend's List 
so, that their friend list will also get updated with you at their friend's list.
We can remove friends from friend's list as well.

Everytime any update happens database gets updated according to the update.

We can view the profiles of our friends in the Freind's list.

Still some more features and some more views will be updated.



