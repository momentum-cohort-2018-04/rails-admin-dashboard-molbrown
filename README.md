# Adding an Admin Dashboard

[Deployed Dashboard](https://protected-inlet-29931.herokuapp.com/admin/)    
[Freeshelf Repository](https://github.com/momentum-cohort-2018-04/rails-freeshelf-1-molbrown)

I used Administrate to create an admin dashboard for my FreeShelf application. I wanted an admin user to be able to:
- Easly navigate through Users, Books, Authors, and Checkouts with practical Index and Show pages.
- Make a new user by adding username and email.
- Create a new book or author.
- 'Checkout' a book for an existing user.
- Edit and Delete Books, Authors, Users, or Checkouts.

![Screenshot](/Screenshot.png)

Administrate is super neat, simple to customize, well-documented, and error messages are extremely informative. It required me to use aliases because of many model associations, and aliasing took some specific syntax. Once we figured that out, Administrate was fun and cool. I learned how to use [**strftime**](http://strftime.net/) for date objects.