create templates
render templates
reuse codes 
write python code in html page 
reuseable title - send title by render function

template inheritance - 
    create block content that can be inherited by child templates
    use layout template as parent of home and about
    Why template inheritance is powerful ?
    ans - now if you want to use bootstrap so instead of using it in home and about now we can only use it in layout.html file

what is cdn? css and js uses it means we need not to download anything

create forms using wtforms apply validators, error handling

always use url_for for linking webpages

# 4. database implementation
use sqlalchemy - here we can represent database structure as classes

set uri's for database , create its instance then define each table as class

 --> test database creation using python interpretor it will create site.db file in same directory 
 --> also test inserting a user and post and then fetch the records


# 5. Convert application into package structure
    error - circular import error
    app.app_context().push() -- run this command to create db from console
    handle duplicate use check before submitting form

# 6. install flask login mangager for handling login
    -validate user while trying to login
    -when user logged in it should show different navbar of home page conatains account tab
    -if account not logged in and trying to reach account page then it should flash message and reach to login page

# 7. finish account page and add functionality to update profile picture and user info
    -create a form like register form change validator as new name and mail should not be same and don't exist
    -create account template
    -if info validated then update db and flash message
    -elseif form should contain current user info
    -now create field to update profile pic
    -add enctype="multipart/form-data" to send proper picture through form
    -set path for picture resize then upload

# 8. add functionality to user to add post, delete and update it
    -create a page and route, login required for this route 
    -create a new form fetch data for user and then render it on home page
    -show profile pic infront of post

# 9. pagination - show fix no of pages on a page 
    -insteading of showing all create paginate object
    -dir(obj) - show all functions of object
    -how to show other pages by passing page no parameter to url
    -now iterate through pages, by iter_pages() function
    -show all the posts by particular user filter by username



