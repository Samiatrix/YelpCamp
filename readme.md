YelpCamp is a website where users can create and review campgrounds. In order to review or create a campground, you must have an account. This project was part of Colt Steele's web dev course on Udemy.

This project was created using Node.js, Express, MongoDB, and Bootstrap. Passport.js was used to handle authentication.

->Features 
* Authentication:
1. User login with username and password
2. Admin sign-up with admin code

* Authorization:
1. One cannot manage posts and view user profile without being authenticated
2. One cannot edit or delete posts and comments created by other users
3. Admin can manage all posts and comments

* Manage campground posts with basic functionalities:
1. Create, edit and delete posts and comments
2. Upload campground photos
3. Display campground location on Google Maps
4. Search existing campgrounds
* Manage user account with basic functionalities:
1. Profile page setup with sign-up
2. Flash messages responding to users' interaction with the app
3. Responsive web design
4. Custom Enhancements Update campground photos when editing campgrounds
5. Update personal information on profile page

-> To Run it locally:
Install mongodb 
git clone https://github.com/Samiatrix/YelpCamp.git 
cd yelpcamp 
npm install 
Create a .env file (or just export manually in the terminal) in the root of the project and add the following:

DATABASEURL='' 
API_KEY='' 
API_SECRET='' 
Run mongod in another terminal and node app.js in the terminal with the project.

Then go to localhost:3000.
