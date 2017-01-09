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
