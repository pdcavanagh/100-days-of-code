# 100 Days Of Code - Log

### Day 1: January 3, 2017

**Today's Progress**: Created quote generator project site using HTML, CSS, Javascript, jQuery, and Bootstrap. 

**Thoughts:** Basic site is build with a quick styling. Randomly selecting a quote from a manually created JSON file. This could easily be extended to a database or API call for more quotes. Tweet button put in as placeholder. Bootstrap is overkill for this project, but could come in handy for a more complex buildout of the project. 

**Link to work:** [Quote Generator](/quote/index.html)
                  [Codepen](http://codepen.io/pdcavanagh/pen/MJWqWy) 

### Day 2: January 4, 2017

**Today's Progress**: Continued work on the quote generator, implemented tweet button.

**Thoughts:** It amazes me how quickly the site was put together yesterday and I was able to have basic functionality working, but today, I spent the majority of my time struggling with Twitter's widget js file. It seems that somewhere in the loading of that script, the DOM no longer had an ID I created to reference the Twitter Intent link with my quote. This was updated through jQuery. Long story short, I don't really like the asthetic of the Twitter tweet buttons and ultimately scrapped the widget js file. Instead I plan to implement my own button styling. It still bugs me that I haven't found out why the widget js file was causing my getElementById to return null, but I'll have to dig into that another time.

**Link to work:** [Quote Generator](/quote/index.html)
                  [Codepen](http://codepen.io/pdcavanagh/pen/MJWqWy) 

### Day 3: January 5, 2017

**Today's Progress**: Finished quote generator project. Implemented Twitter button, default quote on loading, added footer, rearranged button stacking in mobile view. 

**Thoughts:** Today was a refresher on some subtle nuiances of Bootstrap and a reminder that things change between version updates. I was attempting to change the stacking of the buttons for the Tweet and New Quote in the mobile view using the push and pull classes of Bootstrap, but was using an old syntax. I chased that bug around for awhile until I came across the new syntax and a light bulb went off. Coding late at night can have that effect sometimes. The project is completed and fulfills the user stories and the bonus tweet button. It is a simple presentation in terms of styling, but I wanted the words to speak for themselves. I do love Google fonts, though. That's all for tonight. 

**Link to work:** [Quote Generator](/quote/index.html)
                  [Codepen](http://codepen.io/pdcavanagh/pen/MJWqWy) 

### Day 4: January 6, 2017

**Today's Progress**: Began a current weather app. Implemented API calls to HTML geolocation and OpenWeatherMap. Displays user's city and the current temp. 

**Thoughts:** It's always fun to start something new. After a long day, I dove into this project becuase it had a couple straight forward user stories and I could immediately get to work. I quickly created the user account with OpenWeatherMap and was able to skim over the API calls and returned JSON data to see what I would be working with as far as my data source. Next, I implemented the geolocation call and came across some interesting articles on best practices for requesting and utilizing a user's location. That should be helpful for the future. Lastly, I made a quick display of the city and current temp. There is no styling as of yet, but the guts are there. Extracting and displaying the data should be straight forward and will only require a quick review of JSON. The design aspect will probably take much longer, but I'll have fun letting possible ideas percolate. Signing off. 

### Day 5: January 7, 2017

**Today's Progress**: Continued work on weather app. Parsed weather description and applied a title case algorithm. Began styling with center alignment, background weather image, and arial default font. 

**Thoughts:** I spent a bit of time understanding why my syntax wasn't correct when I was coding the algorithm to change the weather description to title case. I was trying to access indivial characters in a javascript string by using the bracket notation, but it wasn't working as I expected. Maybe this is my C habit creeping in or a misunderstanding, either way, I was able to accomplish it through the use of the charAt() function. I am learning little details and reminders about standard javascript objects and prototypes. The reinforcement is positive. Finished my hour with some light styling and an image of an icy Central Park bench for this frigid winter night we have here in Indiana. Weather in Meridian Hills is currently 12 degrees F with clear skies. 

**Link to work:** Creating individual repositories for each project. Will post links soon. 

### Day 6: January 8, 2017

**Today's Progress**: Continued work on weather app, added ability to toogle between F and C for temperature, added gradient background, and added icon to represent current weather. 

**Thoughts:** Finished the user stories for this particular project. I forced myself to knock out the bare bones functionality and meet the user story needs before spending any real time on styling. Overall, I'm pleased. I'd much rather have a working product at the end of the day. I can spend hours on design. I may spend tomorrow diving into implementing some more complex CSS styling. One of today good learning moments was the reminder of how powerful global variables can be in js. I was trying to access a variable in a callback function from a getJSON call, but quickly realized it was as simple as referencing the global variable. However, I did learn about the asyncronicity of the getJSON function calls and learned that with an AJAX call I have the ability to set the asyncronicity to false. Alternatively, if able to, I would be able to construct my function calls in the right order within the callback function. 

**Link to work:** Creating individual repositories for each project. Will post links soon. 

### Day 7: January 9, 2017

**Today's Progress**: Started design of weather app in CSS, implemented custom font 

**Thoughts:** Design is hard. I am not a natural artist, but I am going for it with this design. My goal is to implement a design that mimics the Apollo Guidance Navigation computer from the missions in the 60's. I started with a very nice 7-segment display font and skectched out the basic layout of the computer. I'm implementing everything in CSS and seeing how far that takes me. Should be fun. 

**Link to work:** Creating individual repositories for each project. Will post links soon. 

### Day 8: January 10, 2017

**Today's Progress**: Progress on weather app design, created status lights for temperature, humidity, and pressure; added background; still working the layout 

**Thoughts:** Today was spent mainly on the stylesheet and understanding how layout from scratch works. I'm not using Bootstrap with this project it is forcing me to pay more attention to how a particular layout can be accomplished. I began with a hand sketch of the layout and refer to a photograph of the actual Apollo Guidance Computer (AGC) as I tweak the layout. It's slow going positioning things exactly where I want them while trying to maintain a reasonable approach to the 'proper' way of doing things. For instance, the use of float vs tweaks to the margin and padding to obtain an absolute position. It would be great to get a more experienced designers thoughts of the implementation of the layout. I'll have to reach out to someone upon finishing the first iteration. Overall though, today it is really starting to resemble the original AGC and gave me hope that I'm on the right track. 

**Link to work:** Creating individual repositories for each project. Will post links soon. 

### Day 9: January 11, 2017

**Today's Progress**: Implemented node express server, cleaned up layout  

**Thoughts:** Mixed bag of tasks today. The main goal was to get the layout right and position the info boxes above the 7-segment values correctly. I have settled on a solution that looks reasonable, but I want to consult with a CSS person on how I approached the problem and how best to achieve better results. Also, I spun up a quick node server with express to reinforce some concepts from a meetup tonight. Thoughts for the future: implement call to NASA's APOD API for changing background images and incorporate a radar image from another API service. I did test on my phone and I'll have to put some time into improving the mobile view. Also, I want to start with a default location, e.g. New York City, and then update to local weather at user's request. Currently, the mobile version, at least on iOS, does not request permission to access the user's location and the layout never populates. 

**Link to work:** Creating individual repositories for each project. Will post links soon. 

### Day 10: January 12, 2017

**Today's Progress**: Added current location button and text input for custom location. Added API call to Google geocode for custom location. 

**Thoughts:** I realized that when loading the app in other browsers and on my phone, that the request for location wasn't always consistent. Therefore, I wanted to add a default location and ask the user to input a location and/or submit their current location. The Google Geocode API seems like a good choice due to that fact it can handle all sorts of custom location entries and will return a lat/long that I will use to request weather. 

**Link to work:** Creating individual repositories for each project. Will post links soon. 

### Day 11: January 13, 2017

**Today's Progress**: Finished implementing calls to Google's Geocode API and displaying user entered location weather data, styled buttons, default to New York City weather on load, allow user to request weather at current position through button click. 

**Thoughts:** I'm pleased with the progress today. I have a clean product at the end of it. The app loads and defaults to the weather at New York City and the then the user has the option to enter any location and check their weather (this is cool, I tested with various places around the world and it seems to be working). Additionally, the user can request weather at their current location. This one is a bit trickier. It is straightforward to use the geolocation API to get the current position, but this requires the user's permission. I decided to first present a default that allows the user to see the app and then decide whether or not they would like to submit their location for local weather. The main issues I see for the future are: 1) displaying the correct generic name based on the user's location they entered. Google would return a specific lat/long for a general city and that may correspond to a more specific city than what the user requested. 2) Improve the layout of the numerical values and the info box about the temp, humidity, and pressure. 3) Improve mobile presentation. 

**Link to work:** Creating individual repositories for each project. Will post links soon. 

### Day 12: January 14, 2017

**Today's Progress**: Switched gears and started a nice project, wiki-viewer. Setup repository, node server, and example Wikipedia API calls. Tested tree traversal in javascript for JSON data. 

**Thoughts:** Working more with API calls and loving it. Each time I get to examine how other sites are implementing their API and how to interface. Ran into an interesting issue with Wiki's API, there is a same origin problem with XMLHTTP requests that seems to plague many API calls. This was solved by adding a callback to my query. I'll have to investigate further and maybe write something up on this one. Happy to be implementing some basic tree traversal in javascript. It makes me practice my CS fundamentals moreso than UI layout.  

**Link to work:** Creating individual repositories for each project. Will post links soon. 

### Day 13: January 15, 2017

**Today's Progress**: Finished Wikipedia search API calls and displaying of results, implemented random Wiki article button that loads article 

**Thoughts:** The goal today was to finish the user stories for this project. Goal: accomplished. No styling on the page, but I have a functional search for Wikipedia that displays the title, description, and link to the top 10 relevant sites. Also, there is a random article button that directs to a random Wiki article. The API has its intricacies and I spent time exploring the docs. The API sandbox was helpful at examining the parameters for API calls and expected data. The random page button required two API calls, one to retrieve an article ID and another to get the url. This may be able to be done in two, but it works for now. Happy to be on day 13 of the challenge and going strong. Sleepy, but happy. 

**Link to work:** Creating individual repositories for each project. Will post links soon. This will get done. I promise. :) 
