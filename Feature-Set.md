# The Feature Set


### _Feature Name: Landing Page_
* **User Access Statuses:** _Logged In & Non-Logged In Users, Mods, & Admins._
* **User Stories:** 
    * _As a Logged In user, I want a landing page that includes navigation, featured projects with ratings, popular makers, popular reviewers, and the ability to prepopulate the search page with selected content because all of these features will allow me to get a good idea of the site content and allow me to quickly navigate to different parts of the site. As a Logged In/Current user, I want to receive emails when my projects are reviewed and the ability to reset my password with my email because this makes the site more engaging and accessible._
    * _As a Non Logged In User, I want to see a preview of site content with popular makers, popular reviewers, and featured projects; I want to be able to prepopulate the search page with selected content; I want to be prompted to sign in/sign up; and I want to receive a welcome email when I do sign up because this gives me a good preview of the site and encourages me to engage with the site._

* Search gives dismissible pop-up encouraging sign in, then goes to results page.
* Featured Projects populates with user-generated ratings.
* Clicking a maker in Popular Makers sends user to a account page with information about the selected maker.
* Clicking a reviewer in Popular Reviewers sends user to search page with reviewer entered.

Users receive welcome emails
Users receive emails when their projects are reviewed
Users can reset password via email

### *Feature Name: Search Page*
* **User Access Statuses:** _Logged In Users, Non-Logged In Users, Mods, & Admins._
* **User Stories:** 
    * _As a Logged In user, I want navigation options on the search page; I want the results to include aggregate star ratings; and I want to be able to search projects, reviews, & reviewers because this will let me quickly navigate the site and provide me with robust and helpful results._
    * _As a Non Logged In User, I want results to include aggregate star ratings; I want to be able to search projects, reviews, & reviewers; and I want to be prompted to sign in because this provides me with robust & helpful results and encourages me to further engage with the site._

* Stars on this page are aggregate of all reviews
* Depending on search settings, results can be any combo of projects, reviews, and reviewers.

### _Feature Name: My Projects/Project List:_
* **User Access:** _Everybody._
* **User Stories:** 
      * _As a Logged In user, I want to see a lists of projects with current ratings and I want to be able to click projects and access the project page because this will allow me to find and view quality projects._

      * _As a Non Logged In user, I also want to see a lists of projects with current ratings and I want to be able to click projects and access the project page because this will allow me to find and view quality projects._

* Stars are current rating
* Clicking card opens create/edit/view page for that project

### _Feature Name: Create/Edit/View Project_
* **User Access Statuses:** _Everybody, but Non Logged In users have restrictions_
* **User Stories:**  
   * _As a Logged In user, I want to be able to see all of my projects or projects in general; I want to be able to edit my projects; I want to be able to create projects; and I want to be able to see reviews of my own or other projects because I want to be able to access my content, find new content, fix any content I create, and look over other people’s opinions on my own and other’s content. These opinions let me know about the quality of projects._

   * _As a Non Logged In user, I want to be able to see projects and have access to their reviews because this allows me to find quality projects._
   
* Click Reviews to go to search page w/ results for this specific project
* Click picture for dialogue to change it
* If it’s the current user’s project, they can edit and will have buttons at the bottom to add text and pictures

### _Feature Name: My Reviews/Review List_ 
* **User Access Statuses:** _Everybody, Non Logged In users have some restrictions._
* **User Stories:** 
   * _As a Logged In user, I want to see my reviews and other reviews; I want to be able to edit my reviews; I want to be able to create new reviews; and I want to be able to click a review and be taken to a page(modal) that can let me view or edit that review because I want to engage with the site, provide my opinions on projects, and see others’ opinions._
   * _As a Non Logged In user, I want to see reviews; I want to be able to click on reviews to see individual reviews because this will allow me to find out if the projects I’m interested in are good quality._
   
* Page can be viewed by anyone. Edit controls are disabled for all but logged in users.
* Clicking a card opens create/edit/view review modal. 

### _Feature Name: Review Modal_
* **User Access Statuses:** _Everybody, Non Logged In users have some restrictions._
* **User Stories:** 
   * _As a Logged In user, I want to be able to see individual reviews (my own and others); I want to be able to edit my own reviews; I want to be able to create reviews; and I want to be able to rate individual reviews as helpful or not because this allows me to get more details about a review, it allows me to provide my opinions, and it allows me to help others find the most helpful reviews on projects possible._
   * _As a Non Logged In user, I want to be able to see individual reviews, and I want to be able to rate reviews as helpful or not because it allows me to access more information about the reviews I‘m interested in and I want to help others see the best reviews for the projects they’re interested in._
   
* Can be viewed by anyone. Edit controls restricted to logged in users
* Helpful y/n buttons/rating used to calculate popular reviewers
* Should always load as modal on top of wherever it was linked from
Settings
