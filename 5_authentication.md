# Add Authentication using JWTs

In this assignment, you will include authentication into your application.

## Requirements

1. If you have not already, add user registration to your page.
1. Add User Authentication producing JWTs as cookies into your server.
1. Add User Authentication onto your client to accept the JWTs.
1. Ensure that when a post is created, the proper `user_id` is saved in the database. (remember that we originally specified the seed user id 1).

NOTE: This means the user id will be saved from the server to the client somewhere (either `$localstorage` or a cookie).
