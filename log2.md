# 100 Days Of Code: Round 2 - Log

## Day 1: January 29, 2021

**Today's Progress:** Solved challenges on Codewars with fellow FrauenLoopers JIll and Frannie who inspired me to do another round of 100 Days of Code.

**Thoughts:** It's hard to solve challenges "out loud" when people are watching. But that's something most people know. I also noticed that after the task is solved, I want to get off with it as soon as I can, which I do. Instead, it would be great to think/talk about refactoring, to look at other solutions, to compare.

**Link to work:** [Codewars profile](https://www.codewars.com/users/olhanotolga) — my newly created Codewars profile.

## Day 2: January 30, 2021

**Today's Progress:** Tried to solve the FizzBuzz challenge with Python in a more optimized way. Learned that there are no switch statements in this language, as it appears to be redundant syntactic sugar. Went with if/else blocks. Also, when testing, had to solve the problem of my function not returning anhything by design. Made it return an array of outputs instead. Not sure if it's the optimal way to go about it.

Set up a Flask project to train. For now I'm coding along with a tutorial but I aim to tweak it and make my own :)

**Thoughts:** After React Flask looks like something from the last century. There's even a Bootstrap package which seems to provide some older version of the library!

**Link to work:** [Flask Journal GitHub repo](https://github.com/olhanotolga/flask-journal), [Python challenges](https://github.com/olhanotolga/python-challenges)

## Day 3: January 31, 2021

**Today's Progress:** More Flask training, learned about forms and form validation.

Reviewed user stories and made mockups for my full-stack project at FrauenLoop.

**Thoughts:** Making mockups is excruciating!

**Link to work:** [Flask Journal GitHub repo](https://github.com/olhanotolga/flask-journal)

## Day 4: February 1, 2021

**Today's Progress:** Learning about React router, implementing it in the CountryByCountry project I've been working on. Wrapping my head around all the pushes and redirects.

**Thoughts:** With React Router, I had to change quite a bit of logic to make it all work. Either I'm facing maintainability issues or I simply need to document the logic somewhere (or both).

**Link to work:** [CountryByCountry GitHub repo](https://github.com/olhanotolga/countrybycountry)

## Day 5: February 2, 2021

**Today's Progress:** More React router training. Also started a new project, a small fake e-commerce website. Will be working on it for the rest of the week. Made mobile designs with Canva, implemented the basic React structure.

Started playing around with the cat themes on Canva for the Rent a Cat project. I'm still missing mockups.

**Thoughts:** Canva's applying styles (colors/fonts) to a design makes life much much easier and the projects prettier, although husband says all my creations look pretty much the same :)

**Link to work:** Coming soon...

## Day 6: February 3, 2021

**Today's Progress:** Transformed the base design of my current project into components (pages as I'm using the React router). The main routes are done, as well as the 404 page. Let's see if I manage to do the functionality in 1 day.

**Thoughts:** Looks very good but obviously I want it to function as well. I think I took a bit too much time for the design.

**Link to work:** Coming soon...

## Day 7: February 4, 2021

**Today's Progress:** Created a spreadsheet with data and tried to figure out how to make API calls to a Google Sheet. In the end managed to only convert the spreadsheet to a JSON file and fetch data from it. TO didplay it, howeveer, I had to parse the hell out of my result (because I got the information either by cells or rows only without using the API properly). Displayed the data alright in the end. Also created a bunch of states for the app and enabled the shopping cart (adding and removing items to/from it). For now it all exists as a state, will work on displaying it over the coming days.

**Thoughts:** A very exhausting experience with Google Spreadsheets. Now I'm interested in figuring out how this thing works even more.

**Link to work:** Coming soon...

## Day 8: February 5, 2021

**Today's Progress:** Not much done today:

— Fixed a few styling flaws in the current app.

— Did a challenge-solving session with Jill and Frannie. Jill made an introduction to Leetcode. Very interesting!

**Thoughts:** I'm not very good at low-level algorith problems.

**Link to work:** Coming soon...

## Day 9: February 6, 2021

**Today's Progress:** Working on the webshop project. At the moment, the page with shopping cart is rendered when I click on the cart icon from either Products or ProductDetails page.

At first I was getting an error when following the `'/cart'` route. Turned out the router was looking for a product named `'cart'`, as I specified the path `'/:product'` for the component that displays the current product's details. Changed the path to `'/products/:product'`, and all went as planned.

Update: Finished almost all the basic functionality, apart from registration. Would be awesome to move the users info outside of the app, also add security.

**Thoughts:** This app takes eternity to make...

**Link to work:** Coming soon...

## Day 10: February 7, 2021

**Today's Progress:** Did a marathon working on my webshop simulation app: did functionality for the registration page, also for displaying username in the bottom, a bunch of improvements, a lot of design fixes... Ready to present.

**Thoughts:** Maybe a bit of an overkill, this app. But mine :)

**Link to work:** Coming soon...

## Day 11: February 8, 2021

**Today's Progress:** An extensive learning day with classes & FrauenLoop. Presented my app in the class, got a pat on the back. Still have to do a lot of tweaking. For example, realized that I have no idea what a normal shopping cart looks like inside :) I mean, elements in mine are slightly off, which could make a weird user experience. Anyway, I moved the project into my own repo.

Watched Maria demonstrate creating Python scripts for a database setup.

**Thoughts:** I wonder if I should continue presenting my stuff in the class or maybe sit quietly...

**Link to work:** [BuyByeBuy webshop repo](https://github.com/olhanotolga/buybyebuy)

## Day 12: February 9, 2021

**Today's Progress:** A stressful day: today we learned (at least tried to learn) Redux in the class. Although I could eventually follow today's Redux presentations (after a few iterations), I can't reproduce any of it on my own. It's too much new information for me to click.

After getting totally frustrated, I had a call with a friend who managed to calm me down.

Then I spent some time fixing the Countries API project:

- [x] Added an animated 3rd-party loader
- [x] Enabled hiding the dropdown filter when clicking outside of the container (used somebody's custom hook and integrated it into my component)
- [x] Enabled fetching data only when the country name is set, which freed me from a series of errors in my console before anything loads

Still left:

- [x] Design the 404 page
- [ ] Go to homepage upon clicking on the name in the TL corner
- [ ] Use reducers
- [ ] Store theme choice in localStorage
- [ ] Check for the responsiveness
- [ ] Try using SCSS for styles / Styled Components
- [ ] Replace images with dummies on preload
- [ ] Change the favicon
- [ ] Create a README
- [ ] Check if the project's requirements are met
- [ ] Deploy

**Thoughts:** After the call with my buddy, I have the following takes-away:

- I don't have to know everything, nobody does;
- I don't have to do professional projects "like in real life" because real-life projects differ a lot;
- I need to focus on theory and thinking and trying things out.

**Link to work:** [CountryByCountry repo](https://github.com/olhanotolga/countrybycountry)

## Day 13: February 11, 2021

**Today's Progress:** Started working in a 2-person team on a React Tetris game. We are following a tutorial but hope to refactor it later by adding reducers / using Redux / changing styles, etc.

2nd part of the day: made a 404 page for my countries project. Will see if it doesn't look out of style. Updated the to-do list in the previous day log.

**Thoughts:** The Tetris game is super complicated for me at this point (1 — super counter-intuitive; 2 — I don't have the mindset for games/pure logic yet) but extremely interesting!

**Link to work:** [CountryByCountry repo](https://github.com/olhanotolga/countrybycountry)

## Day 14: February 13, 2021

**Today's Progress:** There was no Feb 12th :)

Been creating templates with Flask & Jinja for my Rent a Cat project. Created registration & login forms, added condions for the routes, sorted out the flash messages.

Set up a Google Maps API key.

Added a Kanban board with to-do cards for the Tetris project, so that I don't forget everything on Monday.

**Thoughts:** Not having designs for the Rent a Cat project is slightly killing me.

**Link to work:** [Rent a Cat repo](https://github.com/olhanotolga/rent-a-cat)

## Day 15: February 14, 2021

**Today's Progress:** Watched Corey Schafer's tutorials and continued to build my Flask training project. This time a lot has been added: user registration (w/ adding to the database), conditional redirects, profile page and a possibility to edit one's account data from there, along with adding/changing profile picture. A lot of pip packages!

**Thoughts:** Got overwhelmed today again because I have too many projects and too little time. I've fallen a bit behind the FrauenLoop schedule/class. Hope to finish it all some day.

**Link to work:** [FlaskJournal repo](https://github.com/olhanotolga/flask-journal)

## Day 16: February 15, 2021

**Today's Progress:** Continued building Tetris with Christin. We finished the game, planned and sketched additional features like adding a how-to-play info block/popup, displaying an upcoming tetromino, introducing a pause button, adding control buttons for the mobile view, etc.

Also: Google Maps API & SQLAlchemy+Flask magic at FrauenLoop.

**Thoughts:** Got a few scares over GitHub collaboration processes. Need to practice that more.

**Link to work:** [Tetris repo](https://github.com/chmette/reactive-tetris)

## Day 17: February 16, 2021

**Today's Progress:** More Tetris. Implemented the functionality to generate and display the upcoming tetromino. Used react-responsive library to display components and values conditionally depending on the screen size (width). Tomorrow is the styling and, hopefully, deployment day.

Submitted my CV to 2 places. Just to see what happens.

**Thoughts:** Job application process and all that stuff is extremely stressful and time-consuming (sum up, write, design, shorten). The work itself is much less so.

**Link to work:** [Tetris repo](https://github.com/chmette/reactive-tetris)

## Day 18: February 17, 2021

**Today's Progress:** More Tetris. Fixed bugs, resolved issues, was making the thing more responsive. Mostly worked via LiveShare (pair programming). Final push tomorrow!

**Thoughts:** This game is a trap!

**Link to work:** [Tetris repo](https://github.com/chmette/reactive-tetris)
