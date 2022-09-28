Capstone 2: Project Proposal

### Destinary

What tech stack will you use for your final project? We recommend that you use React and Node for this project, however if you are extremely interested in becoming a Python developer you are welcome to use Python/Flask for this project.

- The tech stack for this project will include Node, React, Express and PostgreSQL.

Is the front-end UI or the back-end going to be the focus of your project? Or are you going to make an evenly focused full-stack application?

- It will be an evenly focused full-stack application.

Will this be a website? A mobile app? Something else?
- It will be a web application.



What goal will your project be designed to achieve?

- This project will allow users to create their own ‘travel board’ or destination itinerary by saving all the places they would like to visit at any destination on a single board.  Users could search for places of interest at any destination, read reviews and save them to their own board. Users could search for places based on their interests or activity  like arts, entertainment, restaurants, bookstores, shopping etc and save them in one place and retrieve them as needed. They could read reviews, get recommendations and provide their own photos and reviews for places on their boards that they visited. Users could also save related links from other websites.


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
- Travel boards

b. What kinds of issues might you run into with your API? This is especially important if you are creating your own API, web scraping produces notoriously messy data.

- There may be issues with the API going offline or validation errors


c. Is there any sensitive information you need to secure?

- Passwords will need to be secure


d. What functionality will your app include?

Users can:
  - search for businesses by location and category and read reviews
  - register for an account and login to:
    - create travel boards
    - save places
    - delete items
    - search other users in the database by places or locations of interest
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
- When a user signs up or logs in, they will be taken to their profile page where there will be links to create a new board, edit an existing board, get recommendations, search for other users, write own reviews, upload photos and/or website links, share board with other users


f. What features make your site more than a CRUD app? What are your stretch goals?

- Creating secure user accounts using the B-crypt hash, using search functions 
for user lookup and providing recommendations will make this site more than a CRUD app.

- Stretch goals would be to allow users to:
  - control their privacy settings 
  - autocomplete suggestions
  - create or upload a detailed itinerary
  - message other users 
  - share their board on social media or with friends. 