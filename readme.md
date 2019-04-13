# Developer Challenge
Thanks for being interested in a job at Turner.  You will have 24 hours from receipt of this document to:

* Write the code to complete the challenge
* Push it up to a github or bitbucket public repository. We will review this with you during the next step, so don't delete it.
* Send us the URL to your repository.

We will then clone your repository, run the code, and assess your solution.

## The Problem

We would like you to build an application that:

* Search for a movie by its name.
* Display the movies that match the above criteria.
* Allows users to pull up detailed information about a selected movie from the list.
* Authenticates individual users with either guest sessions or normal user sessions (requires user to have registered account with https://www.themoviedb.org/).
* Allows users to rate and favorite movies and persist any ratings/favorites throughout the user session (e.g. refreshing the browser should not cause favorites to be lost).

If the role is more back-end focused we may ask you to provide an API about application usage for integrating with downstream business intelligence applications. Needless to say, if you will be providing an API, you will need to persist user data somewhere. Any data store (PostgreSQL, SQLite, MongoDB, etc.) relational or non-relational should be sufficient. Please do not use a flat file however. The API should be able to provide the following information:

* Users
* Ratings by User
* Favorites by User
* Average Rating by Movie
* Ratings by Movie
* Favorites by Movie
* Most Favorited Movie
* Ratings Since Date
* Favorites Since Date

Feel free to design the API however you see fit, just make sure that the above information can be retrieved easily, without the need for any additional processing or API calls. The API should be expressive without being excessively verbose. It should also return appropriate error codes (e.g. don't send status 500 if an invalid endpoint is called). Please see https://github.com/Microsoft/api-guidelines/blob/vNext/Guidelines.md and https://hackernoon.com/restful-api-designing-guidelines-the-best-practices-60e1d954e7c9 for more API design guidelines.

## Data

The data used for this challenge will be from the https://www.themoviedb.org/ API. The key required for calling this API will be provided to you. Please see https://developers.themoviedb.org/3/getting-started/introduction for further API documentation.

## Code
The application should be written with node.js, using either Vue (http://vuejs.org) or React (https://reactjs.org/) for the front-end framework if applicable.

## Hints

* Do your best to impress us.
* Expect us to Lint your javascript.
* Form is as important as function.  If your app works, but is written like a website from 2001, that would be bad.
* We're suckers for new technologies (i.e. Vue, React, Angular, media queries, MVC 4, Handlebars).
* Creativity: Don't like our requirements? Feel free to enhance this app as you see fit.
* Feel free to host the app somewhere (Azure, EC2, S3, AppHarbor, etc)
