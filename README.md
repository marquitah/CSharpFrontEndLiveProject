# CSharpFrontEndLiveProject
For the last two weeks at The Tech Academy, I've been working on a project with my peers in a team developing a full scale MVC Web Application in C#. This sprint, I was focused on front end stories. We were also exposed to the agile process that mimicked a real-world employee situation with stand ups every day and a code retrospective every Friday. 

Below are descriptions of the front end stories I worked on.

## 1) Redoing the Container Agreement
The typical view on our page should have the bulk of its content within a container. This helps manage the front end styling changes, as we don't need to worry as much about colors disappearing with a changed background if the container things are in stays the same, or close to the same.

There are plenty of containers on our site (indexContainer, defaultContainer, formContainer, <controllerName>Container ... etc. ) and we want the styling of these containers to match for certain pages as follows; 

==> Index, Details, and Delete view pages should share the same container name and style (see example image below). 
==> Create and Edit view page should have the same container name and styling (see example image below). 

NB: Whichever container you use to make the desired styling changes, don't forget to remove the remaining unnecessary containers from the Html and CSS files.

### This story was great because it was a chance for me to go through every view file and see exactly what the styling looked like and what classes were being used for those styles. Then I had to make them all consistent throughout the entire site and remove unnecessary classes or IDs.

## 2) CompanyNews on Dashboard
The company news cards on the dashboard lack some margin between them and some padding-bottom to the container holding them all. And the company news seems different from the other tables on the dashboard (Associated Jobs, User List). All the tables should share the same styling patterns. 

Please apply appropriate styling tweaks that you think fit. 

### We utilize Bootstrap in this project and this was a great chance to learn how to override Bootstrap stylings, especially when dealing with cards.

## 3) CompanyNews on Dashboard Tweak
The color scheme used in the company news container on the home/dashboard doesn't correspond with our root colors (color-palette. ) 
Please do the necessary tweaks to match with our other pages.

### I chose this as sort of a continuation of my last story; it was very similiar so I thought I would knock it out as well.

## 4) Back Endish: ChatMessage AnchorButtons partial views
All our indexes where Edit/Details/Delete/BackToList buttons are, employ the Anchor Button group partials. 

We found out the ChatMessage Index view doesn't make use of these Anchor buttons. 

Please go and implement these button partials for the Edit/Details/Delete/BackToList buttons in the ChatMessage Index view.  

### I haven't been too exposed to back end yet in the live project so this was a great introduction.

## 5) Remove scrollbar from side-nav
The vertical scrollbar at the side-nav-bar doesn't look very cool. Please remove it.

### I've never dealt with side nav bars before so finding where the code was for this was tricky but I figured it out.

## 6) Create User Request Page
The Create User Request Page needs several tweaks. (Find this page in Views>CreateUserRequest>Create )

The Main button, Generate Confirmation Code, needs to be styled like the Back to List button so you can read the text on the button.

The User Role drop down should be styled like the User Name Box

The Back to List Button should be inside the container under the Generate Confirmation Code button. 

### This was a more challenging story as there were lots of tweaks and adjusting to many different elements. The most challenging part was trying to match the dropdown menu to the User Name box as the corners needed to be rounded.

## 7) Mobile-friendly - Schedule Index
Previously we had mobile-friendly pages for all our sites (through the branch AH-5151-MobileFriendlyDesign). But now we are experiencing that some of our pages are not optimized for mobile display. Check out how AH-5151-Mobile FriendlyDesign was implemented in the first place and fix the current bugs for the Schedule index view.

Nb: Please include a screenshot of your final work on the comment section while making the pull request. 

## 8) Home/Index Tweak
1. Remove the container holding cards for the three buttons.  
2. Add a box-shadow to the three cards using the link below. 

https://html-css-js.com/css/generator/box-shadow/
