# Passion For Cars

Live link - https://renaldas0.github.io/Passion-For-Cars/

Passion for cars is a site that aims to attract more people into the car community and serves as a platform for existing car enthusiasts. The target audience is very broad , ranging from kids up to adults of roughly 45 years of age. The site offers a quick insight into the history of the automobile with links that can lead a user to read far beyond just the history, and the possibility to get emails sent about upcoming events depending on the users preference where they can meet other car enthusiasts.

   ![amiresponsive-screenshot](https://user-images.githubusercontent.com/97538312/162216382-1689c6d6-5645-4d0e-be8e-bec141827149.jpg)


## Features
- __Navigation Bar__
  
  - The navigation bar at the top of the website that stays the same across all 3 pages and contains the name of the website in the top left corner,
  which when clicked brings you back to the top of the home page.
   
   ![navigation](https://user-images.githubusercontent.com/97538312/162248981-ce35de63-53a0-4f70-ab70-3d4a750cbac1.jpg)

- __Header__
  - The header in the top left corner shows the name of the website and is clear what this site is supporting/who it is for.
  - The colour used is a hexadecimal with the value #D7A000
  - I chose this colour as it stands out and doesn't blend in to the background colour.

- __Menu__
  - The menu elements follow the same layout, are fully responsive across the 3 pages and adjust depending on the width of the viewport screen.
  - When the screen width goes below 900px the menu elements float left and go under the header.
  - The purpose if this navigation is to allow users to navigate the site easily and clearly.
  - Upon hovering the elements in the menu currently being hovered will change colour to aqua, indicating what the user will select.
  - Additionally the menu has a style added which underlines the current page name the user is on in the menu section.
        
   
   
 - __Landing page image__

   - The landing page has a main image that pops out immediately upon loading to allow the user to see they are on a car site.
   - This image seemed very eye catching to me and aims to attract the attention of anyone who visits the site.
    ![porsche-screenshot](https://user-images.githubusercontent.com/97538312/162434837-c1221453-4a64-4251-a69d-4ff9b6f84e5c.jpg)
    
- __History section__
   - The history section is designed to give the user a snippet of the history of cars and have them interested to learn more. 
   - Existing car enthusiasts may not have known some of the history either so it will be something new for a large majority of users.
   - Clickable links that open up in new browser tabs exist in this section.
   - The first being "History of cars " heading and a link to Nicholas Joseph Cugnot (inventor of the first automobile that could carry passengers).
   - 
   ### History section Images
   - The images are of a Ford Model T and Volkswagen Beetle cars and are shown because the history paragraph mentions these vehicles as the most mass produced vehicles ever.
   - The images help the user get a clear image of the vehicles without the need to go search for them if they are not aware of these cars.
   - The images are also responsive depending on the width of the viewport , on medium devices they go under the paragraph and on small devices one image goes under the other.
   
   ![history-of-cars](https://user-images.githubusercontent.com/97538312/162568139-ba18e9f8-8c98-4d17-a225-a53d21d01c0c.jpg)

- __Footer__
   - The footer at the bottom of every page is the same 
   - The 4 icons are located in the center of the footer and allow users to follow up on this site through social media by clicking on the preferred social media.
   - Each link opens up in a new tab and has aria-labels.

![footer-screenshot](https://user-images.githubusercontent.com/97538312/163669440-e8baff24-eff9-4859-8ea3-e129e318e759.jpg)


 
## Gallery page
   - The images show pictures taken at car events and the type of cars people can come across at these meetups / car shows.
   - The purpose of this is to show users what these car events consist of and the interesting automobiles that arrive.
   - The gallery page contains 8 images and a video that gives the viewer controls of play,pause,volume.
   - The images are separated into columns and these columns adjust depending on the width of the viewport.
   - The final section is there to give a few reasons as to why users should check out the final page and that is to sign up to receive newsletter emails about events.
   
   ![gallery-page](https://user-images.githubusercontent.com/97538312/162588592-7a9e6000-893a-4571-97db-c4cca31ce1ed.jpg)

## Sign up page

   - The sign up form is there so users can select to be emailed on what events they wish to be notified of
   - The form collects the users first name, last name, an email address and they must select 1 of the available options before submitting
   - It is valuable to the user as it provides them with useful information in the future
- __Features__
   - Input fields have a transparent background
   - The border appears when hovering over a specific input field
   - Submit button inverts colours when hovered over
   - Each of the inputs are required

![sign-up-form](https://user-images.githubusercontent.com/97538312/162624456-d2c91861-8143-4f39-b0b0-43f4a5d0ff82.jpg)

## Testing 

   - I tested that this site works on multiple browsers such as Safari, Firefox and Chrome
   - Checked that the site looks good on different viewports such as desktop, mobile phone and tablet by using the link in github pages
   - I have confirmed that the form works and requires an entry into every field and the email entry will only accept email addresses
   - Checked to make sure all text is visible clearly and easy to read
   - All pages work 
   - All the links open in separate browser tabs

## Validator and Lighthouse testing
   - __HTML__
      - No errors were found when i checked the HTML in the official W3C HTML validator - https://validator.w3.org/nu/?doc=https%3A%2F%2Frenaldas0.github.io%2FHTML-CSS-project%2F
   - __CSS__
      - No errors were found when I checked the CSS in the official Jigsaw (CSS) validator - https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Frenaldas0.github.io%2FHTML-CSS-project%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en
   - __Accessibility__
      - I checked that all colours and fonts chosen are easily readable and accessible by running the website through lighthouse in devtools (all 3 pages on desktop          and mobile)
### Index lighthouse screenshot
![lighthouse](https://user-images.githubusercontent.com/97538312/162716401-6f7cecd5-befa-4bee-b0fa-909f24778b70.jpg)
### gallery lighthouse screenshot
![gallery-lighthouse](https://user-images.githubusercontent.com/97538312/163197334-7aa81e2b-640e-4513-9c73-95e8264e7f45.jpg)
### signup lighthouse screenshot
![signup-lighthouse](https://user-images.githubusercontent.com/97538312/163197414-69a1ed5f-9459-4362-9597-d4c77de4caee.jpg)



## Bugs
   - A bug i encountered at the start was with the responsive design of the beetle and ford model t images on devices samller than 470px wide
   - The images would become pixelated due to being sized down too much
   - I fixed this by bringing the images into photoshop and resizing them to less pixels
   
   - There are no unfixed bugs

## Deployment
   The project was deployed to GitHub Pages using the following steps
      - Log in to GitHub and locate the GitHub Repository
      - At the top of the Repository (not top of page), locate the "Settings" Button on the menu
      - Scroll down the Settings page until you locate the "GitHub Pages" Section
      - Under "Source", click the dropdown called "None" and select "Main Branch"
      - The page will automatically refresh 
      - Scroll back down through the page to locate the now published site link in the "GitHub Pages" section
  
## Credits
   - __Content__
   
      - I took inspiration and some styling rules from the CI Love Running Project
      - The colours for the header were discovered using htmlcolorcodes.com (link) - https://htmlcolorcodes.com/
      - History of cars paragraph was from wikipedia - https://en.wikipedia.org/wiki/History_of_the_automobile
      - Nicholas Joesph Cugnot is linked to a wikipedia page - https://en.wikipedia.org/wiki/Nicolas-Joseph_Cugnot
      - I got the icons for social media and the history of cars header from fontawesome.com - https://fontawesome.com/
      - The font for the website was taken from google fonts - https://fonts.google.com/
      - I followed the readme file example from the CI solutions example - https://github.com/Code-Institute-Solutions/SampleREADME

   - __Media__

      - All images were found on pexels.com and pixabay.com (pexels - https://www.pexels.com/ ) (pixabay - https://pixabay.com/ )
      - The video footage was taken from YouTube (Creative Commons) search results


