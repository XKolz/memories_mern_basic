# Memories

![Memories]()

## Introduction

Using React, Node.js, Express & MongoDB you'll learn how to build a Full Stack MERN Application.
The App is called "Memories" and it is a simple social media app that allows users to post interesting events that happened in their lives.

Setup:

- run `npm i && npm start` for both client and server side to start the app

## ----------------

GET method to fetch all the post from the database(Mongodb)
http://localhost:5000/posts

No JSON body needed

## ----------------

POST method to post your content, its viewed on the UI and saved to your database(Mongodb)
http://localhost:5000/posts
{
"title": "Your Post Title",
"message": "Your Post Message",
"selectedFile": "Image_URL or file path",
"creator": "Post Creator Name",
"tags": ["Tag1", "Tag2"]
}

## ---------------

PATCH method to update your context(Update any property_name)(id:654126dbc7c044b42ca35117)
http://localhost:5000/posts/654126dbc7c044b42ca35117

{
"title": "Your Post Title",
"message": "Your Post Message",
"selectedFile": "URL or file path",
"creator": "Post Creator Name",
"tags": ["Tag1", "Tag2"]
}

## ---------------

DELETE method to delete your context from the Website and the database(id:654126dbc7c044b42ca35117)
http://localhost:5000/posts/654126dbc7c044b42ca35117

{
"title": "Your Post Title",
"message": "Your Post Message",
"selectedFile": "URL or file path",
"creator": "Post Creator Name",
"tags": ["Tag1", "Tag2"]
}
