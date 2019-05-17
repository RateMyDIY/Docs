# Architectural Layout
## Front End 
### What technology solution will you use for your front-end? 

* React/Apollo
  * What problems does this solution solve for this specific project? 
      * It provides a flexible development framework with state management and routing for our application and allows us to use all the best features of the JS ecosystem to create the application. 
  * What are the drawbacks of using this solution over alternatives?

* Cloudinary
  * What problems does this solution solve for this specific project?
  * What are the drawbacks of using this solution over alternatives?
* Firebase
  * What problems does this solution solve for this specific project?
  * What are the drawbacks of using this solution over alternatives?


### What library or framework will you be using for styling and presentation?  

* SCSS
  * What problems does this solution solve for this specific project?
  * What are the drawbacks of using this solution over alternatives?


-What library or framework will you be using for styling and presentation?  

Styled-Components for streamlined components and Node-SASS to handle global variables and CSS styles.

What problems does this solution solve for this specific project? 
It allows the team to streamline major component and styling issues by keeping then consistent. 

What are the drawbacks of using this solution over alternatives? 

It’s a little more setup in the beginning, and requires more skill than some UI libraries, but it's not as opinionated.


## Back End
What technology solution will you use for your back-end?


* GraphQL/Nexus/Prisma
  * What problems does this solution solve for this specific project?
  * What are the drawbacks of using this solution over alternatives?
* EasyGraphQLTester for testing GraphQL/Apollo code.
  * What problems does this solution solve for this specific project?
  * What are the drawbacks of using this solution over alternatives?
* Nexus for ORM/query builder.
  * What problems does this solution solve for this specific project?
  * What are the drawbacks of using this solution over alternatives?
* Prisma for interfacing with the databaseand for persisting the aforementioned data.
  * What problems does this solution solve for this specific project?
  * What are the drawbacks of using this solution over alternatives?
* Nodemailer
  * What problems does this solution solve for this specific project?
  * What are the drawbacks of using this solution over alternatives?
* Stripe
  * What problems does this solution solve for this specific project?
  * What are the drawbacks of using this solution over alternatives?



What problems does this solution solve for this specific project?

Apollo and GraphQL work with each other very well, along with the Front-End framework Gatsby, which removes some of the headaches that come with having to find tools that don’t clash with each other.

MongoDB allows for the creation of more flexible data models, and thus more flexible queries, which will eliminate a lot of cognitive overhead for both the back-end team, with implementing the database, and the front-end team, with the various types and shapes of data they might want to store in the database.

Jest is a JavaScript based testing framework for testing, that works out of the box, with several JS based web development, such as React and Vue.

Supertest is an npm package that will allow us to test various parts of the API, so as to make sure the endpoint functionality, the data it depends on, and the data it returns are correct.

Prisma is a type safe system for accessing the database, which is predicated upon ORM’s.


What are the drawbacks of using this solution over alternatives?

Apollo/GraphQL: The main drawbacks of these two solutions are that they will require the team to become familiar with technology that we have not covered previously, which will add cognitive overhead to the development process.

MongoDB: As with Apollo and GraphQL, the main drawback here is that the team will need to become familiar with the nuances of Mongo, which will add cognitive overhead to the development process, however, this will be more of a trade-off because Mongo allows for more freedom with regards to data modeling/storage.

Jest: The main drawbacks here are that Jest is asynchronous, which could lead to false positives or negatives, if the components that it test aren’t fully loaded, along with their data. Also, errors in the application codebase could interfere with test accuracy.

Supertest:The main drawbacks here are that Supertest, being an npm package, may limited in the scope of issues it is able to both detect, and be applied to.


