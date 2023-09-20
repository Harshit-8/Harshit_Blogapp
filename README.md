# Django_Blog
 This is a Django-based web application for a personal landmark blog. The blog allows an admin to post landmarks, which can be viewed by users. Users can explore the places, add them to a "Read Later" list, delete places from the list, view detailed information about each place, leave comments, and manage their own Read Later list

![image](https://github.com/Harshit-8/Harshit_Blogapp/assets/85034142/7979d7b1-c9d9-45fd-91bb-9735994a812c)



 # Table of Contents
1) Installation
2) Usage
3) Features
4) Dependencies

# Installation
1) Clone the repository: git https://github.com/Harshit-8/Harshit_Blogapp.git
2) Navigate to the project directory: cd Django-Landmarks-Blog
3) Install dependencies: pip install django

# Usage
To run the project, use the following command:
python manage.py runserver

# Features
1) Starting Page: The starting page of the blog.

URL: "" (empty string)
View: views.StartingPageView
Name: "starting-page"

2) All Posts: Displays all the landmarks/posts.

URL: "posts"
View: views.AllPostView
Name: "posts"

3) Post Detail Page: Shows detailed information about a specific landmark/post.

URL: "posts/slug:slug"
View: views.SinglePostView
Name: "post-detail-page"

4) Read Later: Allows users to add landmarks/posts to their Read Later list.

URL: "read-later"
View: views.ReadLaterView
Name: "read-later"

# Dependencies
The application is built using Python and utilizes SQLite for data management and templates for rendering views. The following dependencies are required to run the Django Landmarks Blog:

Django
SQLite




 



 

