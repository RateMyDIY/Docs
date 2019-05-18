# Architectural Layout
## Front End 
### What technology solution will you use for your front-end? 

* React/Apollo
  * What problems does this solution solve for this specific project? 
      * It provides a flexible development framework with state management and routing for our application and allows us to use all the best features of the JS ecosystem to create the application. 
  * What are the drawbacks of using this solution over alternatives?
      * There aren't very many for React, as it's a very advanced and stable framework, however Apollo is rather new, and is predicatd upon newer technology, so there may be some edge cases, errors, or gotcha's that are hiding within it.

* Cloudinary
  * What problems does this solution solve for this specific project?
      * It allows for users to reliably upload images for projects from a number of commonly used and well known sources, such as Dropbox, Instagram and Facebook, as well as the users computer.
  * What are the drawbacks of using this solution over alternatives?
      * There's obviously the technical overhead of fully implementing it, and it means a core part of our functionality is relying on third party software, which we don't have control over.
* Firebase
  * What problems does this solution solve for this specific project?
      * It implements OAUTH for a number of commonly used sites for 3rd party authentication, allowing for people to sign up with pre-existing accounts.
  * What are the drawbacks of using this solution over alternatives?
     * Again, it creates a situation where some of our functionality is subject to decisions made by outside parties.


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
      * Apollo and GraphQL work with each other very well, along with the Front-End framework Gatsby, which removes some of the headaches that come with having to find tools that don’t clash with each other.
      
  * What are the drawbacks of using this solution over alternatives?
      * The main drawbacks of these two solutions are that they will require the team to become familiar with technology that we have not covered previously, which will add cognitive overhead to the development process.

* EasyGraphQLTester for testing GraphQL/Apollo code.
  * What problems does this solution solve for this specific project?
  * What are the drawbacks of using this solution over alternatives?
* Nexus for ORM/query builder.
  * What problems does this solution solve for this specific project?
  * What are the drawbacks of using this solution over alternatives?
* Prisma for interfacing with the databaseand for persisting the aforementioned data.
  * What problems does this solution solve for this specific project? 
      * Prisma is a type safe system for accessing the database, which is predicated upon ORM’s.
  * What are the drawbacks of using this solution over alternatives?
* Nodemailer
  * What problems does this solution solve for this specific project?
  * What are the drawbacks of using this solution over alternatives?
* Stripe
  * What problems does this solution solve for this specific project?
  * What are the drawbacks of using this solution over alternatives?

Prisma is a type safe system for accessing the database, which is predicated on ORM's.

