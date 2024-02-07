# Author: Carter Proctor

## Overview

My project is still in its beginning phases. I think my original idea may be too complicated, so I have amended it to focus on hiking and weather forecasts based on the user's geolocation. This is a more focused and attainable goal for the semester. Currently, the project has two working pages along with geotags that show the location of the user, and then grants the options of either searching for a specific location to show hikes or a find hikes near me button that uses the geolocation of the user accessing the website.

My main page, called index, is simple and uses JavaScript and containers along with custom CSS styling to provide a pleasing landing page. It then links using a razor page reference to a page called search results. The search result page is also simple at the moment. It has custom CSS that matches the index page, and a small table that will show hikes in the location the user has provided and ranks them by difficulty. Currently, there are no real trails put in but that will change as the project matures. The search result page also provides links to maps and websites of local hikes to Morgantown, West Virginia. This also is a work in progress.

## Sites Researched

- Alltrails.com
- Hikingproject.com
- Opensummit.com

### Alltrails
When navigating Alltrails, I noticed when clicking on the explore button a “?” followed by my current latitude and longitude. This pinpointed on a map where I was and trails close to my location. I thought this could be helpful when creating my own site so people would not have to be prompted to put in their current location. On inspecting the page I didn’t recognize most of the HTML other than anchor, header and div tags. It seems most of the website is tucked under containers and classes that have no real names.

### Opensummit
While navigating Opensummit, I noted a nav tag that was part of the search bar that seemed like it would be useful to users looking to try different links. I also saw plenty of footers showing the color and border space of the website. Most of it seemed to be comprised of JavaScript and I couldn’t understand it. Under a section of div I found a class that referred to having a light and dark mode option that I thought was a nice touch if a user planned to be on the site for an extended amount of time.

### Weather.com
While navigating Weather, it was the only one of my sites where I found a field set or form tag. Under form there was an autocomplete off function that seemed useful. I also found tags for li and ul for list items and unordered list that seemed like a good road map to help make columns. This site also used plenty of iframes. I think after some research these could make my site look very polished.

## GitHub Research

- **HTML-CSS**: This is a comprehensive search bar with dropdown menus and search functions. It allows configuration of different buttons for pages and a working search function of those pages. It also provides a log in form that would be useful when creating a free version vs a paid version with more options. It also gives access to a sticky nav bar which would look nice when scrolling though options and wanting to change location of target destination.

- **Quickstart-map-js**: This seems to be a great bit of code for including GIS maps and geolocation into my website. Because it will focus on outdoor activities such as hiking different maps will be important. It uses bootstrap and JavaScript to build fully responsive maps.

## Future Enhancements

I would like to add graphics that are pleasing to the landing page and fix the styling so that it adjusts with the window size, currently it looks the best only as a full-screen page. I would like to finish the search function so it actually would show hikes near the location and not just link to a result page that is static. I imagine this will require more complex coding and a database. I would also like to add working maps and GSI data so that a user can get directions to the park and see TOPO maps of the terrain they hike.

## Citations

- **Github.com**: For research on code that could help with my site.
- **W3schools.com**: Used for all kinds of questions I had.
- **Google.com**: Provided a nice CSS hex code map I could drag my mouse over to find the exact color I wanted for my styling.
- **Bootstitch**: Because it was required.
- **ChatGPT3**: All kinds of questions and step by step instructions to build the index page. As well as proofing the occasional error. The prompts below are the main ones that helped me build the pages.
    1. When creating an HTML page with razor pages, does the JavaScript go on a separate page?
    2. Create an HTML page with a search bar and geolocation as a listening function that will link to a new page called search results.
    3. How do I link this to a page called search results?
    4. Using this HTML <form> <label for="LocaitonID">Where do you want to hike?</label> <input type="text" id="LocationID"/> </form>, how do I add an alternate form that says "hikes near me" and use a geolocation listener to link to a separate page?
    5. Can you also add a box that displays the current geolocation of the user accessing the main web page?
    6. Can you add a custom CSS to this HTML page? I would like the colors to and theme to resemble alltrails.com.
    7. How do I move "where do you want to hike" into the text box and make the words disappear when the user clicks on the box to input their choice?
    8. How do I make the table a grid with lines between the columns and rows?
    9. How do I get the two links to be on separate lines on top of each other?

