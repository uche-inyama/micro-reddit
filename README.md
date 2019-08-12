# MICRO-REDDIT

This rails application features a User, Post and Comment Model. It illustrates a system where the user can create posts and comment on them.

## To DO
To run it, clone this repository locally, and run these commands on your terminal.
```
cd ~/micro-reddit
rails console

```
You can the create new users, posts or comments by simply typing 

```

User.create(name: "Example User", email: "user@example.com", password: "foobar", password_confirmation: "foobar")
Post.create(user_id: "user_id", link: "link_address")
Comment.create(user_id:"user_id", post_id: "post_id", body: "any content")

```
on the console prompt.  **NB: Enter the parameters for _id's as intergers**

For more details on how to naviagte through the application, please visit
[link on OdinProject!](https://www.theodinproject.com/courses/ruby-on-rails/lessons/building-with-active-record-ruby-on-rails)
 
## User Model
  A user 'has_many' posts and 'has_many' comments.
  
## Post Model
  A post 'belongs_to' a user and 'has_many' comments.
  
## Comment Model
  A comment 'belongs_to' a user and also 'belongs_to' a post.
  
  
