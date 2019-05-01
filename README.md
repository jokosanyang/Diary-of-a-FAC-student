# :book: Diary of a FAC student 
> Founders and Coders is a non-profit organisation that focuses on developing and running tuition-free, peer-led training programmes in web development, guided by their core values of cooperation, inclusion and social impact.

They run an intensive 16-week full-stack Javascript bootcamp three times a year and I was lucky enough to be selected to be part of the FAC16 cohort running in their London campus from March - June 2019. 

For the first half, every week we 
- completed workshops in a new area
- participated in research afternoons surrounding a number of new topics
- completed a group project consolidating all of the learning outcomes
- delivered presentations
- reviewed another group's code 

For the second half, we worked on two extended projects. One was a cohort-selected student project, and the other was a client-driven [Tech for Better](https://www.foundersandcoders.com/techforbetter/) project to develop a social impact app.

Here is a log of my experiences!

---

### :wrench: Week 1 - Toolkit 
**I learned:** 
- pair programming techniques
- the importance of checking accessibility when programming
- how to code review

**Research topics:**
- command line 
- regular expressions
- accessibility
- CSS conventions

**Project:**
> Create an accessible one-page portfolio website for your team 

![Lucky 13 portfolio website](https://i.imgur.com/khbILNv.jpg)

**[Link to project repo](https://github.com/FAC-Sixteen/w1-t1)**


| Triumphs | Challenges | 
| -------- | -------- | 
| Creating a responsible, accessible website within the given deadline     | Learning to work completely as part of a pair after solely coding alone in the past     | 
| Getting to know the people on the course | Using regular expressions for validation |




---

### :eight_spoked_asterisk: Week 2 - Testing

**I learned:**
- test-driven development
- how to test code using [tape](https://github.com/substack/tape) and measure coverage using [istanbul](https://istanbul.js.org/)
-  about event loops 

**Research topics:**
- Unit vs integration testing
- Technical spikes
- DOM manipulation
- Test coverage

**Project:**
> Use test driven development to create a to-do app with the ability to add a task, delete a task, and mark a task as done

![NotSoWunderlist todo app](https://i.imgur.com/cbd9051.png)
**[Link to project repo](https://github.com/jokosanyang/week2-todo)**

| Triumphs | Challenges | 
| -------- | -------- | 
| Developing better communication skills     | Understanding the tape testing format     | 
| Problem-solving via explaining out loud     | Splitting up tasks fairly between group members  | 

---


### :twisted_rightwards_arrows: Week 3 - APIs
**I learned:** 
- sending an API request with XMLHttpRequest
- about the request-response relationship
- the importance of planning out software architecture

**Project:**
> Create a web app that queries two APIs using xhr requests and document the use of a well-considered software architecture

![intro page](https://i.imgur.com/CfpA5vt.jpg)
![yodariser](https://i.imgur.com/0V0AbHR.jpg)

**[Link to project repo](https://github.com/jokosanyang/week3-agony-yoda)**

| Triumphs | Challenges | 
| -------- | -------- | 
| Learned new CSS animation techniques     | Finding good, key-free APIs  | 
| Excellent planning     | Debugging errors in the console (CORS) | 

---


### :cloud: Week 4 - Node.js 1/2
**I learned:**
- the structure of a server, router and handlers
- what Node is and how to use Node modules
- the importance of code modularisation

**Research topics:**
- Architecting (front-end vs back-end)
- Engineering (node modules)
- Packaging (npm and dependencies)
- Deploying ([Heroku](https://www.heroku.com) and env)

**Project:**
>Create an autocomplete widget which enables users to find and select words from a list of suggestions as they type.
>Host the project on Heroku

![spellchecker](https://i.imgur.com/4UBQGIv.jpg)

**[Link to project repo](https://github.com/jokosanyang/week4-spellchecker)**

| Triumphs | Challenges | 
| -------- | -------- | 
| Successfully used a fetch request for the first time    | Did not manage to design a desktop view |
| Creative brainstorming session     | Hosting the project on Heroku (installed dependencies as devDependencies) |

---


### :ocean: Week 5 - Node.js 2/2
**I learned:**
- how to test server routes using Supertest
- three approaches to error handling
    - error first callbacks
    - try-catch
    - return to caller
- how to make requests from the back-end using the [Request](https://www.npmjs.com/package/request) or HTTP Get module
 
**Research topics:**
* continuous integration
* buffers and streams
* node shell modification
* making requests from the server

**Project:**
> Create a web app which sends API requests from the Node.js server
 
![time to fly](https://i.imgur.com/eShO8aE.png)

**[Link to project repo](https://github.com/jokosanyang/week5-timeToFly)**

| Triumphs | Challenges | 
| -------- | -------- | 
| Clean, modular code     | Merging the responses from 2 back-end API requests into one object to return to the front-end script     | 
| Excellent evenly-split group work | Writing tests | 


---


### :minidisc: Week 6 - PostgreSQL
**I learned:**
- what a relational database management system is and how to use it
- how to use Postgres locally and remotely
- the standard query structure of SQL
- how to test database queries


**Research topics:**
- schemas and relationships
- database setup and maintenance
- script injections/safety issues

**Project:**
> Set up a database connected to a node.js server and use the data to create a dynamic web app

![Lost and Founders database](https://i.imgur.com/Npfoueb.png)


**[Link to project repo](https://github.com/FAC-Sixteen/Week6-project-Onions)**

| Triumphs | Challenges | 
| -------- | -------- | 
| Excellent planning     | Completing project styling  | 
| Working as a team of four the entire time and understanding every part of the code     | Testing the database     | 

---


### :lock: Week 7 - Authentication
**I learned:**
- cookie management
- hashing passwords using bcrypt and JSON web tokens
- session management by signing cookies

**Research topics:**
- HTTP vs HTTPS
- Stateless vs stateful authentication
- Web storage
- Attacks

**Project:**
> Building on an existing project or creating a new one, write an app with a login page and using cookies to store logged in status and username

![Lost and FAC login page](https://i.imgur.com/0qBxZET.jpg)

![Lost and FACactions page](https://i.imgur.com/1qeIcdU.png)


**[Link to project repo](https://github.com/FAC-Sixteen/Week7-project-onions2.0)**

| Triumphs | Challenges | 
| -------- | -------- | 
| Mastering cookies  | Very short of time     |
| Successful password management   | Struggling with callbacks     |

---


### :zap: Week 8 - Express
**I learned:**
- how to set up a project in Express
- templating with Handlebars
- CSS animation


**Research topics:**
- Promises and fetch
- Server-side rendering/Templating
- Express middlewares
- Session-management in Express


**Project:**
> Create an app using an Express server, with a postgreSQL database. Use a handlebars template to render retrieved data server-side.

![submit dream page](https://i.imgur.com/8VAXdkD.png)

![personalised dream diary page](https://i.imgur.com/q9CyuZz.png)

**[Link to project repo](https://github.com/FAC-Sixteen/week8-just-a-dog)**

| Triumphs | Challenges | 
| -------- | -------- | 
| Using the amazing Handlebars helpers!     | Learning the new Handlebars syntax     |
| Quickly understanding Express     | Database testing    |

---

### :hourglass: Weeks 10-16

> In progress...
