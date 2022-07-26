
# MONGS

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### App Ideas
 - An app that creates a platform for young and upcoming artists around the world to showcase their artworks.

### App Evaluation
- **Category:** Exhibition
- **Mobile:** This app would be primarily designed for mobile devices, but it may also be used on a PC. The functionality would not be restricted to mobile devices, although the mobile version may offer additional capabilities.
- **Story:**  Creates a platform for young and upcoming artists around the world to showcase their artworks.
- **Market:** Any aRT lover can use this app.
- **Habit:** This app could be used as often as the user wants depending on their inspiration at any time, and what exactly they're looking for.

## Product Spec

### 1. User Stories (Required and Optional)

** Completed Required Stories**

* The app interacts with a database (e.g. Parse)
* The app integrates with Google maps API for showing users current location, and showing the closest museums and exhibition centres to their location.
* Filtering posts by distance to user
* Using the Tensor Flow image labelling API, users can filter posts matching their interests.
* The user can log in/log out of the app
* The user can sign up as a new user
* The app will have a bottom navigation bar holding the home, compose, location, chat, and profile fragment.
* The app will give the user options to either upload a photo of the artwork or take a new photo of the artwork.
* The details activity of the posts will showcase the art with an animation, and date created.
* The profile fragment will showcase the information entered by the user at signup and all posts made by the current logged in user.
* Calendar external library for the available dates of the artwork
* Create a user interface for cropping and rotating the photos of the artwork.
* Created a user interface for users to view all posts on the maps and query the posts by the distance from their current location.
* Combine query by distance and filter by label search on the map

**Completed Stretch Stories**

* Having a very polished UI
* Users can see location of other users on the map
* Users can comment and like an artwork post
* Users can see the comments of other users
* Users can query posts by distance, and time. 
* A timestamp of when the post was created is available.
* Added a group chat feature for all users
* Delete post feature
* Delete chat feature
* Drawing canvas feature, where users can draw on the screen and also save their drawing to their phone storage.


## Wireframes
<img src="https://github.com/bseyi/Project_Idea/blob/main/IMG_3774.jpeg" width=600>

### [BONUS] Digital Wireframes & Mockups


### [BONUS] Interactive Prototype

## Schema 
#### User

   | Property      | Type     | Description |
   | ------------- | -------- | ------------|
   | author        | Pointer to User| the current user |
   | profileImage         | File     | profile image that user uses |
   | commentsCount | Number   | number of comments that has been posted to the playlist|
   | likesCount    | Number   | number of likes for the playlist |
   | createdAt     | DateTime | date when playlist is selected (default field) |

### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
