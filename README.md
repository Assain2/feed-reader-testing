# UdaciFeeds

## Table of Contents

* [Running the application](#running-the-application)
* [Instructions](#instructions)
* [App Test Units](#test-units)

## Running the application

Open index.html file in your browser.

## Instructions

The application will load available feeds onto the main page. Once clicked, the hamburger icon on the top left corner of the screen will open the menu with different topics. After selecting the feed of the user's interest, the user should click on the title, in order to be redirected to the external page of the article.

### Test units
The application is provided with jasmine's test units. The test units make sure that the application is working as intended. In particular, they test whether:
* the variable `allFeeds` is defined
* each feed in `allFeeds` object has URL defined
* each feed in `allFeeds` object has name defined
* the menu element is hidden by default
* the menu element appears/hides on click
* the `loadFeed` function generates necessary elements of the feed
* the content of feeds is properly updated when `loadFeed` function is done
