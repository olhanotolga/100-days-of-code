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

## Day 19: February 18, 2021

**Today's Progress:** Final push with Tetris. Did a rather big cleanup, tried to implement dropping the tetro continuously with touch & hold but left it for the future. Now we are left with the README and deployment. And presentation on Tuesday.

Continued with Corey Schafer's Flask tutorials, trying to catch up with FrauenLoop.

Watched a recording of last week's job interviews talk with Taledo's CTO (Marcel). Quite nice and structured. It was a tiny bit of preparation before tomorrow's FL workshop. Main takeaways:

1. always clarify the unclear (clarification == communication)
2. ask yourself what asking what you're asking and saying what you're saying brings you

**Thoughts:** Who am I? What do I aspire? Why? What are my goals/vision/mission?

**Link to work:** [Tetris repo](https://github.com/chmette/reactive-tetris)

## Day 20: February 19, 2021

**Today's Progress:** Omg, read about the heap, stack, callback queue, and event loop yesterday. This is [part 1](https://js.plainenglish.io/a-beginners-guide-to-javascript-under-the-hood-bc60fc352163) and that's [part 2](https://js.plainenglish.io/a-beginners-guide-to-javascript-under-the-hood-part-2-89d34a6a09e1) of the article. Very nicely explained!

Continued following Corey Schafer and his Flask blog tutorial. Added pagination.

Attended a workshop on presenting myself as a job seeker. Thought about my vision (destination) and mission (process/activities).

**Thoughts:** As for the Flask blog, I found it very interesting that it's SQLAlchemy that's responsible for the pagination.

As for the workshop, I thought that I would love to help bring clarity into people's lives and help them make informed decisions, through smart tools, quality information, and access to it. From my side, I want my code to be smart and efficient, readable, and concise, and that's something I should be focusing on.

**Link to work:** [FlaskJournal](https://github.com/olhanotolga/flask-journal)

## Day 21: February 20, 2021

**Today's Progress:** Added models to my flask project.

**Thoughts:** That's really hard! I need to read about models and tables in SQLAlchemy and databases in general to figure out how I should structure the thing.

**Link to work:** [Rent a Cat](https://github.com/olhanotolga/rent-a-cat)

## Day 22: February 21, 2021

**Today's Progress:** Got all confused with my Flask project. Started to rethink the structure to make sense of it and be able to make decisions (design, structure, tools, etc.).

**Thoughts:** To fight frustrations or to not allow it in the first place, always start with why (like in having the vision).

**Link to work:** [Rent a Cat](https://github.com/olhanotolga/rent-a-cat)

## Day 23: February 22, 2021

**Today's Progress:** Finished tetris by making the touch & hold on the mobile arrow down control, writing the README, and deploying it together with the classmate.

Watched Maria (FrauenLoop mentor) do magic juggling data between Google Maps API, database (SQLAlchemy), and Flask backend by generating JSON endpoints on the go and reading them.

Watched Corey Schafer implement the reset password functionality and tried to do it on my own with my gmail... Was painful, worked in the end (had to change the PW and launch the app from Terminal — need to debug more to see which one of those did it).

**Thoughts:** A lot of information!

**Link to work:** [Tetris repo](https://github.com/chmette/reactive-tetris) and [deployed Tetris](https://reactive-tetris.netlify.app/)

## Day 24: February 23, 2021

**Today's Progress:** Presented Tetris in class, then got feedback from Frannie about default scrolling behavior (when the browser window is shorter than the game screen, arrow keys do the vertical scrolling — every time one rotates or speeds up the tetromino!). This triggered a series of 'would be also nice' together with Christin, and we got stuck for good fixing, optimizing, and reshaping the layout...

**Thoughts:** Tomorrow, the backend module starts, and I still haven't used reducers...

**Link to work:** [Tetris repo](https://github.com/chmette/reactive-tetris)

## Day 25: February 24, 2021

**Today's Progress:**

1. Started the backend module at DCI. A very exciting day: getting acquainted with Express.js, setting up a backend server, creating routes and returning different types of information through them, fetching data with a frontend client.

2. Continued working on the Tetris layout: this time, I couldn't do much because of sudden resistance and a wave of apathy. It just doesn't work together anymore :(

3. FrauenLoop part: talked to Frannie about databases and models, saw how she did a great job figuring out the structure and code implementation. Continued to follow Corey Schafer & his Flask blog tutorial.

**Thoughts:** The node.js backend parts starts very similar to what we did with Flask. I felt like it's all coming together.

On a different note, I should consider reducing my RAC project to a minimum because it's gotten too big. For example, leave out transactions for now. I can add columns to my database later.

**Link to work:** [creating an API on localhost and fetching it exercise](https://github.com/olhanotolga/ds-01-hello-backend), [Reactive Tetris](https://github.com/chmette/reactive-tetris), [FlaskJournal](https://github.com/olhanotolga/flask-journal)

## Day 26: February 25, 2021

**Today's Progress:**

Learned about POST requests and using the fetch() method with the second parameter on a login page (yes, it can be done with a POST request!).

**Thoughts:** Realized I forgot how to work with react-router-dom (not that I ever worked with it properly), had to battle with routes, exchanging data between components, and conditional rendering. Of course, I could do everything much simpler in the end.

**Link to work:** [branch olha](https://github.com/FbW36/ds-02-posting-data)

## Day 27: February 26, 2021

**Today's Progress:**

1. Talked to Adrian about the final project. We've created an organization, initialized a project, and decided upon the first tasks: watch a course on Styled Components and write user stories.

2. Had a coding session with Frannie and Jill, were solving a Chuck Norris challenge with Regex and binary numbers.

**Thoughts:** Not much done today.

**Link to work:** [Chuck Norris Push Ups Kata](https://www.codewars.com/kata/570564e838428f2eca001d73)

## Day 28: February 27, 2021

**Today's Progress:** Spent several hours starting my Rent a Cat project anew. Created a Kanban board on GitHub, defined the initial user stories, and started making wireframes in Figma.

**Thoughts:** I decided to go with Figma because I might need it at some point in my life. If everyone's using it, maybe I should try as well. It was a very bumpy start until I watched an intro video. Now it's much clearer. It's super powerful but lacks all the colorful stuff and elements that I got with Canva.

**Link to work:** [Rent a Cat](https://github.com/olhanotolga/rent-a-cat)

## Day 29: February 28, 2021

**Today's Progress:** Finished the initial wireframes with Figma. Took a lot of time.

**Thoughts:** Probably the thing I liked the most about Figma (apart from its endless customization possibilities) is the pencil feature!

**Link to work:** [Rent a Cat wireframes](https://www.figma.com/file/SSuwDvGbyKlOmGK5jEsDmN/Mobile-wireframes?node-id=0%3A1)

## Day 30: March 1, 2021

**Today's Progress:** Continued backend with Express.js. Used an interim database solution with lowdb. Made GET, POST, PUT, DELETE requests.

At FrauenLoop, it was all about troubleshooting today. Got a chance to look at people's code and think about it. Let's see how I approach it when my time comes :)

Created a Jira project for simple-commitments. Wow, it was not that easy!

**Thoughts:** Another rather opinionated tool to master: Jira. It has much more than we'll probably use but I hope we'll use as much as we can :)

**Link to work:** [Todo server](https://github.com/olhanotolga/todo-server)

## Day 31: March 2, 2021

**Today's Progress:** An intense day at DCI with our new teacher and a fullstack todo client. Mainly followed along his livecoding.

**Thoughts:** I'm writing this on Thursday, so I already forgot what I was doing on Tuesday, seems so long ago.

**Link to work:** [Fullstack client](https://github.com/olhanotolga/fullstack-client)

## Day 32: March 3, 2021

**Today's Progress:** Today we had a job application workshop at DCI, which means mostly no coding but preparation of the CV and browsing jobs.

Did a Chuck Norris coding challenge on Codewars. Wanted to be fancy and used a recursion but turned out I did not need it at all. Bummer!

Watched a bit of a workshop on design systems. Started a template for Rent-a-Cat.

**Thoughts:** I don't really have the mood for coding these days, my head is stuffed with planning, designing, and job search. All quite stressful.

**Link to work:** Nothing to link to.

## Day 33: March 4, 2021

**Today's Progress:** Day 2 of the job application workshop, I would have preferred it to be a full day of coding. Added a lot of people on LinkedIn, received the nicest recommendation from a classmate <3 Passed the LinkedIn React assessment.

Completed the "Design Systems with React & Storybook" course on FrontendMasters. A lot of new information!

**Thoughts:** It was a great adventure, want more of that! Can't wait to implement all of that in practice!

**Link to work:** Nothing to link to.

## Day 34: March 5, 2021

**Today's Progress:** Brainstormed functionality and defined the main concepts for the final project with classmate (Adrian) — used Miro for that + Jira for user stories.

Codewars challenges with Frannie. Did a few. Forgot how to use Maps (data structure).

**Thoughts:** I enjoy the planning part but the doing part is better.

**Link to work:** Nothing to link to.

## Day 35: March 6, 2021

**Today's Progress:** Did a little bit of designing for Rent a Cat, exercised Python on SoloLearn.

**Thoughts:** Felt guilty that I wasted the entire day doing nothing, mostly resting.

**Link to work:** Nothing to link to.

## Day 36: March 7, 2021

**Today's Progress:** Found the primary, secondary, and tertiary colors for Rent a Cat — added them to my styles document on Figma.

Updated database models in the project, created the skeleton of the index page.

**Thoughts:** I'm thinking a lot about this project but I hestitate to actually work on it because it seems too big. I'm going to try bit by bit. For example, this is what I can do tomorrow and next week:

- update / create skeletons for the basic templates
- test login/registration pages
- see if I got the models right
- add map view
- update routes with the necessary info, so that it all aligns with the DB
- enable offers and requests
- display offers and requests on the map
- style offers and requests on the map
- edit & delete offers/requests functionality
- style the entire thing

**Link to work:** [Rent a Cat repo](https://github.com/olhanotolga/rent-a-cat)

## Day 37: March 8, 2021

**Today's Progress:** Worked a little time with Rent a Cat. Sorting out routes, forms, and models.

**Thoughts:** Spent some time figuring out how to render a link inside a label in a form generated with wtform. Dediced to listen to Pavel and replace it with an asterisk. (I wanted to put a label next to a checkbox, 'I agree to Terms' and link to Terms so that I have both a semantic link and a semantic label).

**Link to work:** [Rent a Cat repo](https://github.com/olhanotolga/rent-a-cat)

## Day 38: March 9, 2021

**Today's Progress:** Writing middleware with Express, using Router. Did an exercise where I had to validate and edit/correct an object with POST requests. Interesting.

Worked on Rent a Cat, started making templates and ended up creating, deleting, and fixing my database. Works for now. It will be a tiny bit easier to add, update, and render data tomorrow.

**Thoughts:** Again, I spent much more time on Rent a Cat than I hoped to spend. More work for tomorrow.

**Link to work:** [Rent a Cat repo](https://github.com/olhanotolga/rent-a-cat)

## Day 39: March 10, 2021

**Today's Progress:** Learning about databases at DCI. Played around with MongoDB, its cloud Atlas (is it a pun?) and Compass. A lot of downloads and installations :)

Worked further on Rent a Cat, Set up the update profile page, and it's a mess! I realized I established the wrong relationships between my models and am trying to access model instances before creating them. Learning about One-to-Many and One-to-One relationships.

**Thoughts:** Needless to say I thought it would be a breeze. But it's not. Especially with the two DB types.

**Link to work:** [Rent a Cat repo](https://github.com/olhanotolga/rent-a-cat)

## Day 40: March 11, 2021

**Today's Progress:** Dreamt of databases.

At DCI, connecting to mongoDB with mongoose, creating schemas and models, doing queries within my API routes. Took some time to read documentation and figure out methods like updateMany() etc. Made a few typos which caused a few hours of my downtime.

Continued to fight with those models in Rent a Cat.

**Thoughts:** I'll need to simplify my RaC routes a bit and split the functionality (also strip it to the minimum). For example, I don't probably need the update profile feature at the moment. Instead, an option to create a profile and view it (or even only dashboard for now).

User registers --> logs in --> create profile (+ cat sitter / cat keeper) --> dashboard --> write offer/request / see updates from other users...

**Link to work:** [Rent a Cat repo](https://github.com/olhanotolga/rent-a-cat)

## Day 41: March 12, 2021

**Today's Progress:** Restructured the models once again, changed relationships between users & profiles, reset the DB, planned conditional rendering in routes.

**Thoughts:** No problem solving session today, no final project discussion. Wanted to spend some more time with my project.

**Link to work:** [Rent a Cat repo](https://github.com/olhanotolga/rent-a-cat)

## Day 42: March 13, 2021

**Today's Progress:** Added profile types and preferred profile types on the profile creation page. Added simple functionality to create updates. Added validators for the start & end dates in the update description.

**Thoughts:** Some more work done.

**Link to work:** [Rent a Cat repo](https://github.com/olhanotolga/rent-a-cat)

## Day 43: March 14, 2021

**Today's Progress:** Got my hands dirty with Google Maps API. Managed to only render the map on the View page and place an Alexanderplatz marker. Spent a lot of time fixing the issue of api_key having the value of undefined. Turned out I just needed to relaunch my terminal after setting the environment variable and my app after importing it...

**Thoughts:** It's a bit frustrating, the amount of time these Google Maps require. But I knew it's not simple.

**Link to work:** [Rent a Cat repo](https://github.com/olhanotolga/rent-a-cat)

## Day 44: March 15, 2021

**Today's Progress:** Wrote a seed script in the class to populate the DB. It involved creating an array of promises and resolving them all.

With FrauenLoop, each of us (almost) presented what she has done over the past few weeks. I can see I'm doing pretty good.

**Thoughts:** Moving slow and steady :) Google Maps API left to be conquered. And a bunch of ther stuff, of course :)

**Link to work:** [Rent a Cat repo](https://github.com/olhanotolga/rent-a-cat)

## Day 45: March 16, 2021

**Today's Progress:** Started working with the classmate on the backend for the Record Store group project. Created the main user routes and tested with Insomnia.

**Thoughts:** Slow but steady. Didn't work on Rent a Cat today :(

**Link to work:** [Record Store backend](https://github.com/TO-RecordStore/recordstore_backend)

## Day 46: March 17, 2021

**Today's Progress:** Finished the backend part of the Record Store project. Spent almost the entire day to populate the database with users (Faker.js) and records (Last.fm API). Were figuring out the asynchronous code (DB/API calls).

**Thoughts:** Group work is pretty tiring but nice. I think I feel more at ease when working with someone else and am more prone to silly typos and inattentiveness. Maybe also to coming up with nice solutions :)

**Link to work:** [Record Store backend](https://github.com/TO-RecordStore/recordstore_backend)

## Day 47: March 18, 2021

**Today's Progress:** Continued working on the Record Store client: created the structure (components and styled components), discussed functionality/architecture.

Managed to plug in the Autocomplete class & create its instance in my Create Profile form of the Rent a Cat project. Used WTForms' hidden fields to grab latitude and longitude. Some progress!

**Thoughts:** Very slow day with a push in the end. Google Maps API is vast and it's easy to get lost in it, however the information is plentiful. Learning: never call the input field "address" when using it with Google Maps API!

**Link to work:** [Rent a Cat repo](https://github.com/olhanotolga/rent-a-cat)