
github: 


# GreenBot Express API Server

This API is responsible to storing and using data that is provided and retrieved by GreenBot. Authentication with Discord is required for any administrative functions but needs to be worked on further.

## Installation

###### Run an install of all packages.

```bash
$ npm Install
```

###### Create .env in the root directory with the format.
```
key=value
```

###### For the following keys:

   * DB_HOST => Available at mongodb. login credentials required for using database.
   * DB_TEST_HOST => required only for testing purposes.
   * CLIENT_ID => Available through discord developer portal. Required for API Authentication
   * CLIENT_SECRET => Also available through discord developer portal.

###### Before deploying bot to Discord, manually insert Discord ID into administrators database. This can be done through the mongodb website or within the mongo console (without the chevrons).

```ruby
$ use mern
$ db.authusers.insert({ user_id: <Administrator ID>, username: <Administrator Username>})
console.log()
```

short questions and answers


a.	What are the most important aspects of quality software?
The most important aspects of quality software are flexibility and extensibility, maintainability and readability, Performance and efficiency, scalability, usability and accessibility, platform compatibility and portability, testability and manageability, security, functionality and correctness etc. which will indeed lead to design, development, build And deployment and hence, operate.



b. What libraries are being used in the app and why?
This app is built on MERN stack. Thus, it uses four open source components Mongo DB for database; Express and Node for backend or server side and React for front end or client side. In this stack every line of code is written in JavaScript, which is used everywhere, both client-side code and server-side code, with one language across tiers without context switching.


c. A team is about to engage in a project, developing a website for a small business. What knowledge and skills would they need in order to develop the project?
First of all a team should have a strong understanding of project, from both client-side and server-side as well. Be prepared with the wireframe and the stack to be used. A well communication with the business owner or a team leader about what exactly needed, like expectations, functionality, and time-frame. On the other hand they should know the team strength and weakness and work on those to overcome. Assign task to each individual or group. A team should know the stack on which they will be working, be able to communicate within the team effetely. Ability to learn and teach is the key factor of a good web developer. And finally, trust yourself and never give up.


d. Within your own project what knowledge or skills were required to complete your project, and overcome challenges?
The project was small but a full stack, therefore we had to use all our learning throughout the course.  From the very beginning we had to use MERN stack including some html, css and pre-built css (bootstrap, bulma) as well. For this particular project a strong understanding of database (mongodb), backend (express, node) and frontend (react) was required. Beside this ability for testing was required as well.  Although the project was split in a group of 3, everyone had their own part to be done.  At the end we had to deal with all the challenges that we faced during development and fixed it all with the help of each other and the instructor and also some online tutorials. Besides the programming knowledge we also required good communication skills, error handling and helping in a team.  We all finally overcame with the hard work, ability to learn and help and with the help of coder academy team.


e. Evaluate how effective your knowledge and skills were this project, using examples, and suggest changes or Improvements for future projects of a similar nature?
The whole project was done based on our knowledge and skills that we learned from here. Strong understanding of the stack used in the projects, some we knew and some we learned during the project.  We were able to complete the projects on time ,working as a team and also with the help of instructor.  Because it was a group, project we all had to split the project according to our strength. We used all our knowledge gained in this few months and still had to learn more during the projects. For future similar projects, I would personally suggest assigning the project by academy rather than asking students to find client. I feel finding client was waste of time and because client might not have much idea about what to add or what they exactly want, the whole project might turn out not to be fruitful. Instead academy would provide different optional projects which demonstrate the best knowledge and outcomes.
