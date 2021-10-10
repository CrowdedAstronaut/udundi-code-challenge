# Project Description:

This was a front-end coding challenge for Udundi, in Austin, TX.

# Project Wireframes

## Desktop Mockup

![udundi-desktop-mockup](https://user-images.githubusercontent.com/65795477/136682690-41406e5e-845b-4b6c-9c6a-ae942e5ba2bc.jpg)

## Desktop Expanded

![udundi-desktop-mockup-expanded](https://user-images.githubusercontent.com/65795477/136682715-e33f05df-b135-40b0-b69e-b21333fd1f11.jpg)

## Mobile Mockup

![udundi-mobile-mockup](https://user-images.githubusercontent.com/65795477/136682735-5d313fd4-3276-41ec-8d94-6159388624df.jpg)

## Mobile Expanded

![udundi-mobile-mockup-expanded](https://user-images.githubusercontent.com/65795477/136682768-10c57c58-fee2-4478-8624-e55f01e67e2c.jpg)

## Performance
![Udundi_Lighthouse_Report_Desktop](https://user-images.githubusercontent.com/65795477/136716499-eeaa8840-c5d3-4af7-9cbf-ef30eca4506e.png)
<img width="360" alt="Udundi_Lighthouse_Report_Mobile" src="https://user-images.githubusercontent.com/65795477/136716503-89254750-9b4a-441f-a07a-75d9a3acccea.png">

## Technologies Used:

HTML
CSS
Bootstrap 5
JavaScript

# User Stories

-As as a user, when I click on the "plus" icon, I want a modal to animate and appear so that I may learn more about the site.

As as a user, when I open this site on a mobile device, I want the layout to shift so that it's a better user experience.

# Setting Up Core Structure

Prior to starting the desktop design, I re-wireframed it with a mobile-first methodology and created that layout first. With the help of HTML/Bootstrap, I centered the background on the HTML element, and then I used a combination of absolute, relative, fixed, and static positioning in order to achieve this layout. Layering the containers on top of each other required use of the z-index property.

# Focusing on User Experience / Accessability

With the mindset of "mobile first" elements are stacked on the site. One of the concerns was making the modal center to the page on mobile. By using a @media query with a max width of 600px, the site is centered on an iPhone13. I arranged the rest of the elements using a combination of Bootstrap 5 classes, Flexbox, and vanilla CSS.

# Problem Areas/Blockers/Details
-The original Sketch mockup used the Essones font, but the wireframes above show Helvetica. Essones is correct, and that's what the site was built with.

-My goal was to build this project using a NPM paired with SASS in order to normalize it for deployment. However, in order to hit my MVP on time, I opted for the "quick and dirty" installation of Bootstrap 5 using direct links to the CDN. There is a .gitignore and a package.json file attached to the repo, but they aren't currently part of the project.

-The modal animation was a challenge that I'm still wrestling with as of this commit.

-The gradient underline on the modal header is another challenge that I'm still contemplating.

-Getting the H1 to disappear when the modal opens. I could have eventually accomplished this through JS, by adding a variable, a target, an event listener, and a function that would add a class of "active" onClick. Then I could target the active class to make it hidden. It just hasn't happened as of this commit.

-Some pixel perfect tweaks for different screen sizes/resolutions.

# Future Directions

In the future, I'd like to utilize more of Bootstrap's built in classes and SASS to normalize the stylesheet for deployment in the wild. I'd also like to rebuild it using functional components, AJAX, and VueJS which is Udundi's current JS framework of choice.
