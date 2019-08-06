# MICRO-REDDIT

This rails application features a User, Post and Comment Model.

## User Model
  A user 'has_many' posts and 'has_many' comments.
  
## Post Model
  A post 'belongs_to' a user and 'has_many' comments.
  
## Comment Model
  A comment 'belongs_to' a user and also 'belongs_to' a post.
  
  
