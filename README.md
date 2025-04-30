Original App Design Project - README Template


Noted

Table of Contents

Overview
Product Spec
Wireframes
Schema


Overview
Description

Noted is a mobile app that lets users gather their favorite quotes. The app has an easy-to-use interface that allows users to search through quotes, and categorize quotes. In addition, users have the ability to look at their saved quotes and remove quotes. The app is ideal for anyone who wishes to record significant quotes from films, literature, or their favorite celebrities.



App Evaluation

Category: Productivity, Lifestyle
Mobile:  iOS app
Story: Users can collect and manage their favorite quotes easily.
Market: Individuals who love quotes, journaling, and self-improvement.
Habit: Frequent use as users continue to add and organize quotes.
Scope: Initially, the app will feature basic functionality for adding, categorizing, and viewing quotes.


Product Spec
1. User Stories
Required Must-have Stories

- As a user, I want to be able to save quotes to look at on a later date.
- As a user, I want to be able to remove/delete quotes if necessary.
- As a user, I want the app to be easy to navigate. 



Optional Nice-to-have Stories

- As a user, I want to be able to share my saved quotes with friends. 
- As a user, I want to search for specific quotes. 
- As a user, I want to be able to filter my quotes based on my mood.


2. Screen Archetypes
Homescreen: 
The home screen will display a sample of your currently saved quotes alongside “Change quotes “ and the “ Save quote” buttons 

Favorite Quote screen:
This screen will display all quotes that have been saved by the user 

Detail screen (Has not been added):
This screen will display your saved quotes and will allow the user to click on the quote and see the author of the quote.

3. Navigation
Home screen: 
Displays the list of quotes, and options to change the quote or save the quote
Favorites screen:
Displays quotes that the user has marked as favorites.

Flow Navigation (Screen to Screen)

Home Screen: 
Once the “Save Quote” Button is pressed, the user can navigate to the Favorites screen and see a list of quotes they have saved.

Favorites screen:
After saving a quote, the user can now see the quote/quotes on this screen, and can navigate back to the home screen when finished.

Schema

Model name 
Description 
Quote
Represents a quote with text, author
User
Represents a user with a list of favorited quotes.


Models
[Add table of models]

Networking

Endpoint:api.quotable.io
Purpose: Fetch a random quote from the API.

Request:

Method: GET

URL: http://api.quotable.io/random

Response:

Data Type: JSON

Response Structure:
text: The quote text (String)
author: The author of the quote (String)

Function: fetchQuoteFromAPI

Returns: A Quote object containing text and author.
