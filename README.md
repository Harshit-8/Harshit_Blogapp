# Django_Blog
 This is a Django-based web application for a personal landmark blog. The blog allows an admin to post landmarks, which can be viewed by users. Users can explore the places, add them to a "Read Later" list, delete places from the list, view detailed information about each place, leave comments, and manage their own Read Later list

 ![image](https://github.com/Harshit-8/Harshit_Blogapp/assets/85034142/d9455285-83da-4d67-afed-eb5102b8a2b0)
 ![image](https://github.com/Harshit-8/Harshit_Blogapp/assets/85034142/d6b56768-b4ad-43fc-8d7f-79d79fa699d4)
 ![image](https://github.com/Harshit-8/Harshit_Blogapp/assets/85034142/23cd89df-9b03-4a1e-bc19-9e7bc75d2b75)
 ![image](https://github.com/Harshit-8/Harshit_Blogapp/assets/85034142/f3aeefef-193a-49a9-a87c-9f5c3543984f)
 ![image](https://github.com/Harshit-8/Harshit_Blogapp/assets/85034142/a0fd6435-d6e7-4e96-8187-a46e307cf874)
 ![image](https://github.com/Harshit-8/Harshit_Blogapp/assets/85034142/12dd3c5d-77b8-4115-a40c-42753a8a0d49)
 ![image](https://github.com/Harshit-8/Harshit_Blogapp/assets/85034142/200c04ac-db11-43b2-8fa7-033afdb5909a)


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




 



 

