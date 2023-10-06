# YelpCamp
YelpCamp is a full-stack web Application  designed to feature, rate, and review different campgrounds, 
The app performs CRUD operations for users, the campground, and the reviews. 

YelpCamp will play an essential role in making decisions like choosing a campground. This system heavily relies on individuals voluntarily submitting reviews to build a reputation for nearby businesses.

Functionalities : 
 
1. First of all, the User can register and log in to implement authentication. Used Passport.js for that purpose
2. Users can create, edit, and remove campgrounds. For authorization, In order to review or create a campground, you must be logged into your account. A user can only edit or delete his campgrounds or reviews
Users can review campgrounds, and edit or delete their review
3. A map has also been displayed for better searching. While Creating a campground, when a user enters a location, the map finds and shows it automatically with the help of the location geocoding feature of the Mapbox API.
Campgrounds are marked on a cluster map using Mapbox API. Every Campground has its location displayed separately on a map
4. Client-side and server-side validations are done. 
5. Images of campgrounds are uploaded to Cloudinary. We can add multiple images for a campground. Images can be added and deleted after the creation of Campground. 
6. Sessions and cookies were used



This project is being created using Node.js, Express, MongoDB, Javascript, EJS, CSS , and Bootstrap. Passport.js is used to handle authentication.



