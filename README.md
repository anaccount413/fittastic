# Module 2 Group Assignment

CSCI 5117, Spring 2024, [assignment description](https://canvas.umn.edu/courses/413159/pages/project-2) 


## App Info:


* Team Name: Team1
* App Name: Fittastic
* App Link: https://proud-sea-01d6a930f.5.azurestaticapps.net/


### Students

* First Last, x500@umn.edu
* Mouachee Thao, thao0896@umn.edu
* Anas Mohamed, moha1325@umn.edu
* Ji Moua, moua0345@umn.edu
* Alexandra Delacruz, delac105@umn.edu

## Key Features

**Describe the most challenging features you implemented
(one sentence per bullet, maximum 4 bullets):**

* MAP Api/location integration for finding nearby gyms
* Camera device integration for progress photos
* The recommendation feature for the user after they submitted their weight form
* Using bulma.io, a CSS framework, to be responsive to mobile apps

Which (if any) device integration(s) does your app support?

* Camera
* Geolocation

Which (if any) progressive web app feature(s) does your app support?

* Mobile App supported



## Mockup images

**[Add images/photos that show your mockup](https://stackoverflow.com/questions/10189356/how-to-add-screenshot-to-readmes-in-github-repository) along with a very brief caption:**

![](https://media.giphy.com/media/26ufnwz3wDUli7GU0/giphy.gif)

Note about mockup, specifically signed in vs signed out user experiences. Signed out users can only see the home page and information about the site (about/feature pages). We showed this in the mockup by including a sign in button on the pages where the user is not required to be signed in, and a sign out button on the pages a user is required to be signed in on. This is to indicate that only signed in users can access those pages, so they will always see the sign out button. For the pages like about/features/homepage, any user can see those, but we used sign in button there to show that users who are signed out also have access to them. 

PAGES
Homepage
![](/mockup_images/img_1.png?raw=true)

About page
![](/mockup_images/img_2.png?raw=true)

Feature page
![](/mockup_images/img_3.png?raw=true)

Sign in page (very similar to signup)
![](/mockup_images/img_4.png?raw=true)

Weight and Goal Page (also linked to from weight/goal update)
![](/mockup_images/img_5.png?raw=true)

Workout 
![](/mockup_images/img_6.png?raw=true)

Diet Log
![](/mockup_images/img_7.png?raw=true)

Progress
![](/mockup_images/img_8.png?raw=true)

Food/Workout Recommendations
![](/mockup_images/img_9.png?raw=true)

Nearby Gyms
![](/mockup_images/img_10.png?raw=true)

Link to mockup on moqups(anyone with a link can view) https://app.moqups.com/rnvNMBGVNLe6AttHQcD4C0pk03e5npmu/edit/page/a71d0c683 
## Testing Notes

**Is there anything special we need to know in order to effectively test your app? (optional):**

* The user must create an account and login to access the features. If the user does not have an account, then the user can only access the features, about, and homepage.
* We initially had recommendation feature but due to time constraints, we were unable to implement it into our website.



## Screenshots of Site (complete)

**[Add a screenshot of each key page](https://stackoverflow.com/questions/10189356/how-to-add-screenshot-to-readmes-in-github-repository)
along with a very brief caption:**
* This is the homepage/ladnding page of the website for new users and old users
![](/final_images/image1.png?raw=true)
* This is the workout page where the users can add a workout routine to their calender to keep track of their progress
![](/final_images/image2.png?raw=true)
* This is the diet log page where the users can add any food consumptions to keep track of their calories and proteins
![](/final_images/image3.png?raw=true)
* This is the map showing users where any gym are located near them. Clicking on the pin will give them an address and link to Google Maps
![](/final_images/image4.png?raw=true)
* This is the update page allowing users to update their progress such as their goals and their new weight from working out
![](/final_images/image5.png?raw=true)


## External Dependencies

**Document integrations with 3rd Party code or services here.
Please do not document required libraries (e.g., React, Azure serverless functions, Azure nosql).**

* Library or service name: description of use
* FullCalendar React/Javascript Library: used to display events on a calendar
* GoogleMaps & react-geolocated Libraries : used to display the map and get current location
* Calorie Ninja API : used to get nutrition facts when user search for food
* Bulma.io : used for responsiveness and styling

**If there's anything else you would like to disclose about how your project
relied on external code, expertise, or anything else, please disclose that
here:**

* none
