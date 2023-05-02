Download Link: https://assignmentchef.com/product/solved-coen278-assignment-2-sinatra
<br>
In this assignment, use Sinatra web development framework, to implement a simple bet web application.

You web application will create these different views:

When user come to the gambling site, user is presented with a login in view. The login/password information are in a database table as plain text. (you need to initialize this table in advance)

if user is logged in, user is presented with a view for betting (just like the example in class except user use a form to submit bet information) you will display text showing if user has won or lost. also in this view, you will also need to show two set of data,

one set is on the left, these are total values during this logon session these values are 0 after login, and will be saved in session hash,
 but after logout, you need to add these to the database table,

The value in database table are total values for this user since first time login.

so each time the user login, you will  retrieve these values from database table  and display them at the bottom.

and each time user logout, you need to add session value into these value and restore in the database table. the logout button will clear the session and return to login page.