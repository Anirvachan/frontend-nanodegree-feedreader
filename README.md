# Feed-reader testing with Jasmine

## Tests written

1. Wrote a test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.

2. Wrote a test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.

3. Wrote a new test suite named "The menu".

4. Wrote a test that ensures the menu element is hidden by default. 

5. Wrote a test that ensures the menu changes visibility when the menu icon is clicked. This test has two expectations: does the menu display when clicked and does it hide when clicked again.

6. Wrote a test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container. loadFeed() is asynchronous so this test wil require the use of Jasmine's beforeEach and asynchronous done() function.

7. Wrote a test that ensures when a new feed is loaded by the loadFeed function that the content actually changes. Remember, loadFeed() is asynchronous.

## Getting started

1. Download this Github repository onto your local machine.

2. Unzip the files.

3. Navigate to the sub-directory where index.html is located, and

4. Open it in your browser.

####Alternately, 
If you wish to view the application and the tests on Github pages, please go [here](http://anirvachan.github.io/frontend-nanodegree-feedreader/)