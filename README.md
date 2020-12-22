# The Adventure Begins

![Color palette](/docs/Am-i-responsive.png)

## User Experience (UX)

---

-   ### User stories

    -   #### As a regular user I need to:

        - Immediately recognize the purpose of the web page.
    	- Easily access key information about the festival, such as locations and events.
    	- Be able to sign up as a member.

    -   #### As a member I need to:

        - Have a list of all events and locations so I can plan my business accordingly.

-   ### Design
    -   #### Colour Scheme
        The main colors used throughout the page are: 
        -   **#eaeff0** for the background of the page. 
        -   **#06273c** for the header, the footer and modal bodies. 
        -   **#d6dee1** for the text in header, footer and modals. 
        -   **#a2bdc7** for the background of the "locations-dates" section. 
          
        All of these are part of the ***Artic Winter Color Palette***, and these choices were made taking contrast as the most important factor, and because they complement the snowy, chilly feel that is built around this particular festival.	
        
        ![Color palette](/docs/Colors.png)

    -   #### Typography
        -   Two main fonts were chosen for this page: 
            -   **"Dancing Script"** for most of the titles with **"Cursive"** as a fallback, this was chosen to represent the fun and entertaining, yet elegant and organized part of the the festival. 
            -   **"Comfortaa"** for the rest of the text, with **"sans-serif"** as fallback, this gives the page a stylish feel while remaining legible enough.
    -   #### Imagery
        -   A carousel below the header was chosen to highlight some of the attractive elements of the festival as soon as the user loads the page.
        -   The image in the about-us section was chosen to show a festival that depicts people enjoying the event, so everyone gets to see what to expect whenever they attend the festival.
        -   The activities section has interactive images of the activities available, they were made interactive so people relate to their dynamic and fun nature instead of static images that might look boring.

*   ### Wireframes

    -   Mobile Wireframe - [View](https://github.com/JuanBrachoDev/Milestone-One/blob/master/docs/Mobile.png)

    -   Desktop Wireframe - [View](https://github.com/JuanBrachoDev/Milestone-One/blob/master/docs/Desktop.png)

## Features

---

-   ### Fixed header
       Allows the user to easily navigate the page without needing to scroll up to find the section they need while keeping the brand in the field of view.

-   ### Join Us Modal
       Enables regular users to become members, getting access to all the benefits listed in the page. The modal only asks for the minimum amount of information required to process the request.

-   ### Locations & Dates
       Following a minimalistic design, this section shows the dates, full address, and an interactive map ***(Google Maps)*** for the locations of the festival.

-   ### Interactive Images
       Provides the user with dynamic images that draw user engagement without hindering navigation.

-   ### Footer
       Compacts important information like social media links and the copyright disclaimer, that are easily accessed either by scrolling down, or by clicking the appropiate "Contact Us" button in the navigation bar.

## Technologies Used

---

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1. [Bootstrap 4.4.1:](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
1. [Hover.css:](https://ianlunn.github.io/Hover/)
    - Hover.css was used for most of the buttons in the page to make them interactive while being hovered over.
1. [Chrome DevTools:](https://developers.google.com/web/tools/chrome-devtools)
    - Chrome's DeveTools were used throughout the project to test the layout and make the necessary adjustments.
1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Dancing Script' and 'Comfortaa' fonts into the style.css file which are used on all sections throughout the page.
1. [Google Maps API iframe Generator](https://developers.google.com/maps/documentation/embed/map-generator)
    - Google Maps were embedded in the Locations & Dates section to provide a visual cue for the users that compliments the written address.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used in the footer to add recognizable social media icons for aesthetic and UX purposes.
1. [jQuery:](https://jquery.com/)
    - jQuery came with Bootstrap to make the page responsive but was also used for the smooth scroll function in JavaScript.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the [Mobile](https://github.com/JuanBrachoDev/Milestone-One/blob/master/docs/Mobile.png) and [Desktop](https://github.com/JuanBrachoDev/Milestone-One/blob/master/docs/Desktop.png) wireframes during the design process.
1. [Am I responsive:](http://ami.responsivedesign.is/)
    - Used to efficiently test different resposive layouts and provide the header image for the readme file.

## Testing

---

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](https://github.com/JuanBrachoDev/Milestone-One/blob/master/docs/HTML-validation.png)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](https://github.com/JuanBrachoDev/Milestone-One/blob/master/docs/CSS-validation.png)
-   [Google Chrome Lighthouse](https://developers.google.com/web/tools/lighthouse) - [Results](https://github.com/JuanBrachoDev/Milestone-One/blob/master/docs/Lighthouse-results.png)

### Testing User Stories from User Experience (UX) Section

-   #### As a regular user I need to:

    - Immediately recognize the purpose of the web page.
        > The user is greeted with the brand, a carousel of images showcasing the theme of the festival, and a short introduction that explains what the festival is about.
        
    - Easily access key information about the festival, such as locations and events.
        > The user can either scroll to the **locations-dates** and **activities** sections, or find the respective buttons in the navigation bar, with the addition of the fixed header, this functionality is available at any point in the navigation of the page.
    
    - Be able to sign up as a member.
        > The user is able to access the **join-us** section and click the join us button to open a modal with a form, by filling and submitting it one of the organizators will get in touch and complete the member sign-up.
    

-   #### As a member I need to:

    - Have a list of all events and locations so I can plan my business accordingly.
        > Members can easily find detailed information in the **locations-dates** section regarding the dates of the festival with their full addresses, and a list of the fun activities available for all attendants in the **activities** section.

### Further Testing

-   The Website was tested on Google Chrome, Microsoft Edge and Mozilla Firefox browsers.
-   The website was viewed on a variety of devices such as Desktop, MacBook Pro, Samsung J7, Samsung Galaxy S20+.
-   A large amount of testing was done to ensure that all pages were linking correctly.
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.


### Known Bugs

-   The modal loads zoomed-in on mobile devices.
-   The image in the modal is a couple pixels short of the modal's background, so it shows a bit of it around it instead of covering it completely
-   The Join Us button's mouseover effect doesn't work on the bottom half of the button.
-   The button that submits the modal and shows the thank you message isn't able to load the next modal and submit the form at the same time without extra JavaScript code, feature in development.

## Deployment

---

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [Milestone One GitHub Repository](https://github.com/JuanBrachoDev/Milestone-One)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://juanbrachodev.github.io/Milestone-One/ ) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/JuanBrachoDev/Milestone-One)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/JuanBrachoDev/Milestone-One)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/JuanBrachoDev/Milestone-One
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/JuanBrachoDev/Milestone-One
> Cloning into `Milestone-One`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Credits

---

### Code

-   [Bootstrap4](https://getbootstrap.com/docs/4.4/getting-started/introduction/): Bootstrap Library used throughout the project mainly to make site responsive using the Bootstrap Grid System.
-   [Hover.css](https://ianlunn.github.io/Hover/): For the hover effects applied to buttons throughout the page.
-   [Hyde-Design](https://www.hyde-design.co.uk/joomla-bites/80-create-a-css-slideshow-no-javascript-required): For the carousel slideshow at the start of the page.
-   [Free Frontend](https://freefrontend.com/css-image-effects/): For the rotating images effect in the **activities** section.
-   [Code Institute](https://codeinstitute.net/): For the code used in the social media links in the **footer**.
-   [Stack Overflow](https://stackoverflow.com/): As a general point of reference.
-   [W3Schools](https://www.w3schools.com/): As a general point of reference.

### Content

-   [Saint Paul Winter Festival](https://www.wintercarnival.com/) Inspiration for the webpage's theme and layout.
-   [Colorlib](https://colorlib.com/etc/regform/colorlib-regform-3/): Inspiration for the member modal's layout.

### Media

-   All Images were taken from [Pexels](https://www.pexels.com/)

### Acknowledgements

-   My Mentor Narender for continuous helpful feedback.

-   Tutor support at Code Institute for their support.