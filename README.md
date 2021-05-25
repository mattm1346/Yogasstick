# YOGASSTICK, Yoga for Beginners

This is a yoga website designed to help beginners get started with yoga. Included are some beginner techniques for users to either get started on their own at home, or to have a basic understanding of what they will learn in the class should they decide to book.

The website can be used on a desktop computer, laptop computer and mobile phone. Providing great user experience at home or on the move.

## User Experience

**Target audience**

The target audience for Yogasstick are beginners to yoga who wish to learn more about yoga, and experienced people to yoga who wish to book a class.

The website is clearly displayed in order to make it as easy as possible to navigate through each page. Therefore, users of all ages and technological skill will be able to use the website with no difficulty.

Beginners to yoga will want to learn the techniques to yoga which Yogasstick has a dedicated page to do just that. Beginners may also wish to join a yoga class in order to learn in a classroom environment and to build relationships with other members. Yogasstick has a booking page where users can see what time and day is suitable for them and a details page where they can book their place for a lesson.

All users will want to practice yoga in a safe environment. Yogasstick therefore offers the opportunity to practice yoga in their home via the techniques page. Should users wish to book a class, there is a capacity limit which is displayed on the bookings page. This is to ensure the safety of all members by allowing everyone to social distance while the covid-19 pandemic continues.

## User Stories

1. As a novice to computers, I want the easiest way to get around the website so I am not wasting my time and getting lost.
End user goal: Navigate around the website. End business goal: Keep users using website and not leaving in frustration. Acceptance criteria: Create Navigation bar with links to all pages and highlight to inform what page user is on.

2. As a beginner to yoga, I don't feel confident practicing in a class with other people. So I want the ability to learn yoga at home alone and not feel embarrassed.
End user goal: Learn yoga from home. End business goal: Start users using website and booking classes. Acceptance criteria: Create 'Techniques' page with list of basic poses but not all so user will book classes to learn more.

3. As user who is terrible with directions, I want the ability to find where the studio is so I can get to the class on time. 
End user goal: Locate the studio. End business goal: Get users in the studio. Acceptance criteria: Embed map from 'Google Maps' with clear label telling user what map is off. Also add address to footer of the page so user can find address easily.

4. As a parent I have limited free time, so when I go to the class I want to do yoga and not be turned away due to capacity. I want the ability to book classes. End user goal: Book classes. End business goal: Get users to book classes. Acceptance criteria: Create form on 'details' page with ability to book classes by name to reserve place.

## Wireframes

Using the software, 'Balsamiq Wireframes' I created a very basic structure to plan how I initially wanted Yogasstick to look.

![index](https://github.com/mattm1346/Yogasstick/blob/master/assets/screenshots/wireframes/wireframe_index.png)

The homepage was always planned to be welcoming, with a big greeting and hero image of yoga. In respect to the user story #1 (The Novice) the homepage has clear links via the nav bar and in the intro-text to help with navigation.

![techniques](https://github.com/mattm1346/Yogasstick/blob/master/assets/screenshots/wireframes/wireframe_techniques.png)

I wanted the techniques page to be clear and simple. I didn't want to overcrowd the page with text and images. Therefore it has some simple techniques that a beginner to yoga can do with an image and short, clear instructions to follow.

![tips](https://github.com/mattm1346/Yogasstick/blob/master/assets/screenshots/wireframes/wireframe_tips.png)

I originally called the 'Schedule' page the 'Tips' page. With the 'Tips' page I planned to involve some helpful advice to help with yoga and wellness. But I decided to delete the 'Tips' page in favor of the 'Schedule' page and include tips in the 'Techniques' page.

![contact](https://github.com/mattm1346/Yogasstick/blob/master/assets/screenshots/wireframes/wireframe_contact.png)

The 'Booking' page started as the 'Contact' page and included a class timesheet of the classes and the ability to book. There's also a map embeded to allow for the user to locate the studio where classes are held.

## Features

**Homepage (Index.html)**

The homepage is the face of the site and first introduces the user to Yogasstick. It includes a hero image of a woman doing yoga by a lake which draws the user's eye while also encapturing what the website is about, yoga.

**Techniques (Techniques.html)**

The techniques page is where the main information of yoga is held. There are five beginner level techniques each in their own division, with a description of the technique and an image to accompany and further explain what the user should be doing.

**Schedule (Schedule.html)**

The schedule page is all about getting the user to book a class. Here we start with a full list of times that the studio will be holding classes for yoga. Under this, there is a disclaimer notifying the user that class availability is limited due to the coronavirus pandemic (although this website is completely fiction, I thought it would be a good idea to show how it can adapt to changing social times).

There is also a map embeded from google maps (https://www.google.co.uk/maps/). The studio location is shown on the map which is interactive. This is to help users find the location of the studio.

**Booking (Details.html)**

The booking page is where the user can book their class. It has a functioning form that requires the user's; first name, last name, email address and what time and date they would like to book. 

Under the form, there are three icons from Font Awesome (https://fontawesome.com/) reminding the user to stay safe. In the coronavirus pandemic, the three main rules to stay safe were to: wash hands, wear a face mask, and keep a two meter distance from others. The icons on the website include a short description to remind the user to keep themselves and each other safe.

**Nav-bar**

On each page, there is a navigation bar with links to each page to allow for easy navigation.

![Navigation bar](assets/screenshots/nav_bar.jpg.png)

**Footer**

On each page, there is a footer with icons from Font Awesome that are linked to their corresponding website (Facebook, Twitter, Instagram, Youtube, Pinterest). There is also an address of the studio and the yogasstick email address.

![Footer](assets/screenshots/footer.png)

**Audio**

The techniques page has three audio files from Soundbar (https://app.soundstripe.com/) with the ability to be played by the user.

![Audio](assets/screenshots/audio.png)

**Timesheet**

In the schedule page, there is a table element with a list of the available times that a user can book a class at the studio.

![Timesheet](assets/screenshots/timetable.png)

**Map**

Also on the schedule page, there is an interactive map from google maps (https://www.google.com/maps) to help the user locate the studio.

![Map](assets/screenshots/map.png)

**Form**

On the details page, there is a signup form for the user to book a place at a class.

![Signup Form](assets/screenshots/form.png)

**Future Updates**

1. *Zoom class*: Due to the pandemic, there are limited spaces available in the class and some users may be shielding at home. It would be wise to add a video element that connects to a live zoom feed that is held during some of the classes. This would enable users who could not book a place in the class to still practice yoga taught by an instructor from the safety of their homes.

2. *Class Booked*: If a class is at maximum capacity, currently there is no way of telling users that a class is booked out. This counter-affects the user story #4 (The Parent) who has limited time and will not be content arriving at the studio to be turned away. It is therefore needed to add an aspect of booking a class that is full to be unavailable. Such as not an option on the dropdown selector in the details form.

3. *Clearer Technique Image/ Video*: In the techniques page, the images that accompany the text only show the end technique. It could be clearer by either adding a video of the technique or adding a before image. For example, the 'sphinx' position says to 'lie on your stomach' which could be the starting image and followed by the end position.

**Technology Used**

*Google Maps*

Google maps has the feature where you can copy a html code and paste into your own html.

![Google Maps Code](assets/screenshots/map-code.png)

*Soundstripe*

I downloaded three mp3 files from Soundstripe (https://app.soundstripe.com/) and embeded them as audio into the code.

*Love-Running*

From the Love-Running project that I worked on whilst following videos from The Code Institute, I copied code from my repository (https://mattm1346.github.io/Love-Running/) that I used as a template for the **navigation-bar** and **footer social icons**.

*Pexels*

All of the images are from Pexels (https://www.pexels.com/). They provided very high quality images that were relevant to the site. I selected the image I wanted and downloaded from the site itself then saved the image to my Gitpod folder.

![Pexels download button](assets/screenshots/pexels.png)

*Font Awesome*

I used icons from Font Awesome (https://fontawesome.com/) and copied the link it provided to make the website more appealing to the user.

![Font Awesome Code Download](assets/screenshots/fontawesome.png)

**Testing**

Using W3C validator (https://validator.w3.org/) I ran each html page through.

*May 17 2021* The 'index.html' page was successful and resulted in no errors.

[Index W3C] https://github.com/mattm1346/Project_1/blob/master/assets/screenshots/testing/17.05.21/testing_homepage.jpg.png

*May 17 2021* The 'techniques.html' page was unsuccessful and resulted in 22 errors.

[Techniques W3C] https://github.com/mattm1346/Project_1/blob/master/assets/screenshots/testing/17.05.21/testing_techniques.jpg.png

*May 17 2021* The 'techniques.html' page was successful and resulted in no errors.

[Techniques W3C FIXED] https://github.com/mattm1346/Project_1/blob/master/assets/screenshots/testing/17.05.21/testing_techniques_FIXED.jpg.png

*May 17 2021* The 'schedule.html' page was successful and resulted in no errors.

[Schedule W3C] https://github.com/mattm1346/Project_1/blob/master/assets/screenshots/testing/17.05.21/testing_schedule.jpg.png

*May 17 2021* The 'details.html' page was unsuccessful and resulted in 7 errors.

[Details W3C] https://github.com/mattm1346/Project_1/blob/master/assets/screenshots/testing/17.05.21/testing_details.jpg.png

*May 17 2021* The 'details.html' page was successful and resulted in 0 errors.

[Details W3C FIXED] https://github.com/mattm1346/Project_1/blob/master/assets/screenshots/testing/17.05.21/testing_details_FIXED.jpg.png

*May 19 2021* Used the website (https://webformatter.com/) to correctly change the format of all html pages.

*May 19 2021* Ran each page through W3C validator to check that changing the format caused no errors.

[Index W3C] https://github.com/mattm1346/Project_1/blob/master/assets/screenshots/testing/19.05.21/testing_homepage(19.05.21).jpg.png

[Techniques W3C] https://github.com/mattm1346/Project_1/blob/master/assets/screenshots/testing/19.05.21/testing_techniques(19.05.21).jpg.png

[Schedule W3C] https://github.com/mattm1346/Project_1/blob/master/assets/screenshots/testing/19.05.21/testing_schedule(19.05.21).jpg.png

[Details W3C] https://github.com/mattm1346/Project_1/blob/master/assets/screenshots/testing/19.05.21/testing_details(19.05.21).jpg.png

Each link within the website has been tested to work with no errors so the end goal for user #1 (The Novice) has been reached.

The techniques page has clear instructions for learning yoga at home so the end goal for user #2 (The Beginner) has been reached. But could be improved with the future update of adding zoom classes.

The address of the yoga studio is visible on the footer of each page and a map is embeded on the schedule page so the end goal of user #3 (Terrible with Directions) has been reached.

The website has a signup form for the user to book their place at a class by name and recieve an email confirmation. So the end goal for user #4 (The Parent) has been reached.

**Different Devices**

![Homepage Devices](assets/screenshots/devices/homepage%20multi%20device.png)

![Techniques Devices](assets/screenshots/devices/techniques%20multi%20device.png)

![Schedule Devices](assets/screenshots/devices/schedule%20multi%20device.png)

![Booking Devices](assets/screenshots/devices/details%20multi%20device.png)

Screenshots taken from the website http://techsini.com/multi-mockup/index.php.

## Deployment

Yogasstick has been successfully deployed on GitHub and a live link can be found here: https://mattm1346.github.io/Yogasstick/

To deploy, I went to 'Yogasstick/settings/pages' and selected the 'master' branch. Yogasstick was then saved and a notification told me that deployment was successful.

## Credits

*Content*

After designing the initial wireframe of Yogasstick, I found these websites which all have the option to book a class to practice yoga in a studio. These helped to produce the final product with the implement of the booking page and schedule page.

* https://www.orangeyoga.co.uk/

* https://www.paperdressyoga.co.uk/

* https://www.yogam.co.uk/

Yogainternational.com was one of the only websites I found that provided information on how to perform yoga techniques through it's use of recorded classes.

* https://yogainternational.com/

The main focus of these websites was to sell merchandise such as yoga books and audio podcasts. They did not seem very useful as a website that teaches yoga but more as a website that promotes material that teaches yoga.

* https://yogaphysics.com/

* https://dagmarspremberg.com/

*Media*

* https://www.pexels.com/

* https://app.soundstripe.com/

*Acknowledgments*

* https://mattm1346.github.io/Love-Running/

* https://learn.codeinstitute.net/