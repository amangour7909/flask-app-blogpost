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
    
