
# APP_NAME_HERE(TBD)

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### App Ideas
 1) An app that cretes a playlist of songs depending on the mood of a person

### App Evaluation
- **Category:**
- **Mobile:**
- **Story:**
- **Market:**
- **Habit:**
- **Scope:**

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* The app interacts with a database (e.g. Parse)
* The app integrates with at least one SDK or API
* The user can log in/log out of the app
* The user can sign up as a new user
* The app has multiple views
* The app uses at least one gesture (e.g. double tap to like, e.g. pinch to scale) 
* The app incorporates at least one external library to add visual polish
* The app uses at least one animation (e.g. fade in/out, e.g. animating a view growing and shrinking

**Optional Nice-to-have Stories**

* Having a very polished UI
* Having a great App Idea that could be a real product
* user can like the suggested playlist
* User can comment on the suggested playlist
* User can see the day the playlist was selected
 

### 2. Screen Archetypes

* [list first screen here]
   * [list associated required story here]
   * ...
* [list second screen here]
   * [list associated required story here]
   * ...

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* [fill out your first tab]
* [fill out your second tab]
* [fill out your third tab]

**Flow Navigation** (Screen to Screen)

* [list first screen here]
   * [list screen navigation here]
   * ...
* [list second screen here]
   * [list screen navigation here]
   * ...

## Wireframes
[Add picture of your hand sketched wireframes in this section]
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
