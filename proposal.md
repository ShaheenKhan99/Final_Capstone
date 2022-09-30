Capstone 2: Project Proposal

###TripCards

What tech stack will you use for your final project? We recommend that you use React and Node for this project, however if you are extremely interested in becoming a Python developer you are welcome to use Python/Flask for this project.

- The tech stack for this project will include Node, React, Express and PostgreSQL.

Is the front-end UI or the back-end going to be the focus of your project? Or are you going to make an evenly focused full-stack application?

- It will be an evenly focused full-stack application.

Will this be a website? A mobile app? Something else?
- It will be a web application.



What goal will your project be designed to achieve?

- This app will be a destination focused travel social network where users can create “tripcards” that list places and/or activities based on their interest for any destination, share their tripcards, follow other users and make itinerary recommendations 
- Users can search for places or activities such as arts, entertainment, restaurants, bookstores, shopping etc., view ratings, read reviews and save the places or activities to their own personalized destination “tripcard”. Users can create tripcards for each destination they plan to visit. Users can also provide their own photos and reviews for places that they visit as well as save related links from other websites.



What kind of users will visit your app? In other words, what is the demographic of your users?

- Anyone who likes to travel or make travel plans or destination itineraries will find this app useful


What data do you plan on using? How are you planning on collecting your data? You may have not picked your actual API yet, which is fine, just outline what kind of data you would like it to contain. You are welcome to create your own API and populate it with data. If you are using a Python/Flask stack are required to create your own API.

- The app will use multiple endpoints from the Yelp API to access data. Data to be used will include:
  - business search - by keyword, category or location
  - business details - name, address, phone number, photos, rating
  - business match - find a business that matches exact input location 
  - reviews - get up to three review excerpts for a business


In brief, outline your approach to creating your project (knowing that you may not know everything in advance and that these details might change later). Answer questions like the ones below, but feel free to add more information:

a. What does your database schema look like?

The database will have:
- Users - username, first name, last name, email address and password
- Businesses - category, name, address, phone number, image url, Yelp rating, reviews
- User resources - photos, website links, files?
- TripCard - location, username, businesses, user resources

b. What kinds of issues might you run into with your API? This is especially important if you are creating your own API, web scraping produces notoriously messy data.

- There may be issues with the API going offline or validation errors or changes made to the API. It would be important to write tests for all the endpoints, periodically run tests against all relevant endpoints and regularly monitor the API documentation to be aware of any changes


c. Is there any sensitive information you need to secure?

- Email addresses, passwords  and photos are sensitive information. Password will be hashed using Bcrypt. User permission will be required for photos.


d. What functionality will your app include?

Users can:
  - search for businesses by location and category and read reviews
  - register for an account and login to:
    - create tripcards
    - save places
    - edit/delete items
    - search and follow other users in the database by places or locations of interest
    - mark places as visited 
    - write reviews of places visited
    - upload their own photos
    - save website links for related content 
    - get recommendations for places


e. What will the user flow look like?

- The homepage will have links to the signup page and login page
- The homepage will have a form for any user (registered or not) to search for places by location and category 
- The homepage will also have a link to view top destinations/places 
- Only logged in users will be able to view details for places they click on
- When a user signs up or logs in, they will be taken to their profile page where there will be links to create a new tripcard, edit an existing tripcard, get recommendations, search for other users, write own reviews, upload photos and/or website links and share tripcards with other users


f. What features make your site more than a CRUD app? What are your stretch goals?

- Creating secure user accounts using the B-crypt hash, using search functions 
for user lookup, following users and providing recommendations will make this site more than a CRUD app.

- Stretch goals would be to allow users to:
  - control their privacy settings 
  - autocomplete suggestions
  - create or upload a detailed itinerary
  - message other users 
  - share their tripcard on social media or with friends. 