# solid-spork
Module 18 Challenge: NoSQL Social Network API

# Description
a social network api backend 

# Author
Daniel H. Lewis

# Demonstration
https://drive.google.com/file/d/13xOxvmha5fskGYRQQISyGM-g2n20WOWM/view

# User Story
AS A social media startup

I WANT an API for my social network that uses a NoSQL database

SO THAT my website can handle large amounts of unstructured data

# Acceptance Criteria
GIVEN a social network API

WHEN I enter the command to invoke the application

THEN my server is started and the Mongoose models are synced to the MongoDB database

WHEN I open API GET routes in Insomnia Core for users and thoughts

THEN the data for each of these routes is displayed in a formatted JSON

WHEN I test API POST, PUT, and DELETE routes in Insomnia Core

THEN I am able to successfully create, update, and delete users and thoughts in my database

WHEN I test API POST and DELETE routes in Insomnia Core

THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list

# Dependencies
`npm i express`

`npm i mongoose`
