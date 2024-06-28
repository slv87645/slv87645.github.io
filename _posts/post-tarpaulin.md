---
title: "Lightweight Course Management API"
last_modified_at: 2024-06-28T19:15:02-05:00
categories:
  - Blog
---
This API was built for my Cloud Application Development course. It encompassed all the topics that were covered throughout the quarter.
The API was deployed using Google App Engine and CRUD operations were performed on data stored in Google's Datastore. Image files were uploaded to Google Cloud Storage.
The API was tested using an extensive testing suite ran on Postman.

The Tarpaulin REST API has 13 endpoints, most of which are protected. 
The protected endpoints require a valid JWT in the request as Bearer token in the Authorization header. Each user in Tarpaulin has one of three roles: admin, instructor, and student.

GitHub Link: [Tarpaulin](https://github.com/slv87645/Lightweight-Course-Management-API)

Functionality:


![routes](/assets/images/TpRoutes.jpg)
