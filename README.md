# Feed Reader App as Testing Suite example for Jasmin Tests
This Respository contains the 5th Project of the Udacity Frontend Nanodegree.
The Goal is to get in touch with Jasmin - A testing framework for Javascript.

With writing the desired tests, we should learn test-driven development.

# How to use this repository
Clone this repository and open the index.html in your browser

Check out the demo https://leisa218.github.io/feedreader-app/.

# Tests written in this App
1. Test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
2. Test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
3. Test suite named `"The menu"`.
4. Test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
5. Test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
6. Test suite named `"Initial Entries"`.
7. Test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
8. Test suite named `"New Feed Selection"`.
9. Test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
