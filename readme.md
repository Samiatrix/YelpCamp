YelpCamp is a website where users can create and review campgrounds. In order to review or create a campground, you must have an account. This project was part of Colt Steele's web dev course on udemy.

This project was created using Node.js, Express, MongoDB, and Bootstrap. Passport.js was used to handle authentication.

->Features
Authentication:

User login with username and password

Admin sign-up with admin code

Authorization:

One cannot manage posts and view user profile without being authenticated

One cannot edit or delete posts and comments created by other users

Admin can manage all posts and comments

Manage campground posts with basic functionalities:

Create, edit and delete posts and comments

Upload campground photos

Display campground location on Google Maps

Search existing campgrounds

Manage user account with basic functionalities:

Password reset via email confirmation (disabled)

Profile page setup with sign-up

Flash messages responding to users' interaction with the app

Responsive web design

Custom Enhancements
Update campground photos when editing campgrounds

Update personal information on profile page

Improve image load time on the landing page using Cloudinary

Use Helmet to strengthen security

-> To Run it locally
Install mongodb
git clone https://github.com/Samiatrix/YelpCamp.git
cd yelpcamp
npm install
Create a .env file (or just export manually in the terminal) in the root of the project and add the following:

DATABASEURL='<url>'
API_KEY=''<key>
API_SECRET='<secret>'
Run mongod in another terminal and node app.js in the terminal with the project.

Then go to localhost:3000.
