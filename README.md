# CIS-228-Assignment-3-Clayton-D
Assignment 3 project, focusing on a Todo app with API.
Name: Clayton Dalton
Class: CIS 228 - Advanced Web Page Coding
Date: 11/21/2026

# Program Details
11-21-2026
This program can be used to make a todo list for a user.

To run the program, I had to use python3 manage.py runserver, as for some reason regular python would not work.

When running the server, you can go to /api/ to view the current todo list, with /api/1/ offering a more focused view that
only shows the first todo item. the number behind /api/ can be increased and set to whatever specificed todo entry you want to view.

To add a new todo item, you can go to /admin/ and after entering in the superuser account, here being 'test' for both email and password,
you can add a new todo entry.

# Issues
For some reason when running the server, it will show an error screen saying that it could not find the urls for either the admin or
the api. Despite this you can still go to the respective sites by adding it into the url bar at the top.