<h1 align="center">Freelance Photographers Website</h1>

<img src="documentation/screenshots/responsive-screenshot.PNG">

[View the live project here.](https://connorsargent.github.io/FreelancePhotographerWebsite/index.html)

The primary goal of this project is to provide a clean and professional website for a freelance photographer, which showcases the photographers work in a categorized gallery and a blog with recent work and events, the website will also provide a clear and friendly contact form for anyone interested in a photo shoot and links to various social media platforms to bring more attention to the photographer.

## User Experience (UX)

-   ### User stories
 
    -   #### First Time Visitor Goals

        1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the photographer.
        3. As a First Time Visitor, I want to look for the photographers work to learn more about the photographers work. I also want to locate their social media links to see their followings on social media to determine how trusted and known they are.
        3. As a First Time Visitor, I want to be able to easily navigate throughout the site to find contact information and booking photography shoots.

    -   #### Returning Visitor Goals

        1. As a Returning Visitor, I want to find information about upcoming events.
        2. As a Returning Visitor, I want to find the best way to get in contact with the photographer with any questions I may have.
        3. As a Returning Visitor, I want to find social media links.

    -   #### Frequent User Goals
        1. As a Frequent User, I want to check to see if there are any new work added to the gallery.
        2. As a Frequent User, I want to check to see if there are any new event posts.

-   ### Design
    -   #### Colour Scheme
        -   The main colors used are black and shades of blue to convey a professional aesthetic.
    -   #### Typography
        -   The Montserrat font is the main font used throughout the whole website with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. Montserrat is a clean font used frequently in programming, so it is both attractive and appropriate.
        -   The Spartan font is the font used for headings throughout the website with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. 
    -   #### Imagery
        -   Imagery is important. The large, background hero image is designed to be striking and catch the user's attention.

*   ### Wireframes

    -   Desktop/Tablet Wireframes - [View](https://github.com/ConnorSargent/FreelancePhotographerWebsite/blob/master/documentation/wireframes/Desktop%20Wireframes.pdf)

    -   Mobile Wireframe - [View](https://github.com/ConnorSargent/FreelancePhotographerWebsite/blob/master/documentation/wireframes/Mobile%20Wireframes.pdf)

 - Changes to desktop wireframes:
     * Navbar aligned to the right and navbar contact button is now a nav link, changed for aesthetic purposes.
     * Footer logo removed as navbar is now fixed and social links and copyright text on oposite sides of footer, changed for aesthetic purposes. 
     * Event page cards layout changed so smaller events have smaller cards whilst bigger more important events have a full page width card.

- Changes to mobile wireframes:
     * Nav bar is now located and fixed to the top of the page with a hamburger menu, changed for aesthetic purposes. 
    * Gallery images are now shown as one img per row, as two images were too small for smaller devices.

## Features

-   Responsive on all device sizes

-   Interactive elements

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1. [Bootstrap 4.4.1:](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
2. [Hover.css:](https://ianlunn.github.io/Hover/)
    - Hover.css was used on the Social Media icons in the footer to add the float transition while being hovered over.
3. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Titillium Web' font into the style.css file which is used on all pages throughout the project.
4. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
5. [jQuery:](https://jquery.com/)
    - jQuery came with Bootstrap to make the navbar responsive but was also used for the smooth scroll function in JavaScript.
6. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
7. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
8. [Figma:](https://figma.com/)
    - Figma was used to create the wireframes during the design process.

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

-   [W3C Markup Validator](https://validator.w3.org/#validate_by_input) 
<img src="documentation/tests/html-test.PNG">

-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
<img src="documentation/tests/css-test.PNG">

- Lighthouse testing desktop/mobile
   * lighthouse test for all pages except the Gallery came to the results shown below:

<img src="documentation/tests/lighthouse-test-screenshot.PNG">

   * Lighthouse testing on the gallery page came to the results shown below, which initially were a lot lower. I raised the performance by using tiny png to make the img sizes smaller and I also used lazy loading.

<img src="documentation/tests/lighthouse-gallery-screenshot.PNG">

### Testing User Stories from User Experience (UX) Section

-   #### First Time Visitor Goals

    1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the Photographer and potentially book a photoshoot.

        1. Upon entering the site, users are automatically greeted with a clean and easily readable navigation bar to go to the page of their choice. Underneath there is a Hero Image with Text and a "Book a shoot!" Call to action button.

<img src="documentation/screenshots/screenshot-1.PNG">

        2. The user has two options, click the call to action button which will allow the user to learn more about the photographer and book a photoshoot or scroll down which will allow the user to learn more about photoshoots with links to about & enquire and the respective galleries.

<img src="documentation/screenshots/screenshot-2.PNG">

    2. As a First Time Visitor, I want to be able to easily be able to navigate throughout the site to find content.

        1. The site has been designed to be fluid and never to entrap the user. At the top of each page there is a clean navigation bar, each link describes what the page they will end up at clearly.
        2. On all pages the Navbar is fixed to the top of the page to ensure the user always has somewhere to go and doesn't feel trapped as they get to the bottom of the page.

    3. As a First Time Visitor, I want to look for the photographers recent work to understand what their users think of them and see if they are trusted. I also want to locate their social media links to see their following on social media to determine how trusted and known they are.
        1. When the user opens the Recent page they will be presented with social media links at the top of the page which is then followed by the photographers most recent work in date order.

<img src="documentation/screenshots/screenshot-3.PNG">

        2. The user can also scroll to the bottom of any page on the site to locate social media links in the footer.
        3. At the bottom of the About & Enquire page, the user is told underneath the form, that alternatively they can contact the organisation on social media which highlights the links to them.

<img src="documentation/screenshots/screenshot-4.PNG">        

-   #### Returning Visitor Goals

    1. As a Returning Visitor, I want to find the photographers most recent work.

        1. This is shown in either the recent page or gallery.
        2. The links can be located either on the nav bar or in the about section on the About & Enquire page.

<img src="documentation/screenshots/screenshot-5.PNG">

    2. As a Returning Visitor, I want to find the best way to get in contact with the Photographer with any questions I may have.

        1. The navigation bar clearly highlights the "About & Enquire" Page.
        2. Here they can fill out the form on the page or are told that alternatively they can message the organization on social media.
        3. The footer contains links to the organizations Facebook, Instagram, Pinterest and Youtube pages.
        4. Whichever link they click, it will be open up in a new tab to ensure the user can easily get back to the website.

<img src="documentation/screenshots/screenshot-4.PNG">

    3. As a Returning Visitor, I want to be able to book photoshoots.

       1. The home page hero image had a call to action button to "book a shoot!".
       2. The navigation bar clearly shows a About & Enquire page. 

<img src="documentation/screenshots/screenshot-1.PNG">   

-   #### Frequent User Goals

    1. As a Frequent User, I want to check to see if there are any newly added Gallery photos.

        1. The user would already be comfortable with the website layout and can easily click the navigation bar link

<img src="documentation/screenshots/screenshot-6.PNG">         

    2. As a Frequent User, I want to check to see if there are any new Recent work.

        1. The user would already be comfortable with the website layout and can easily click the Recent link.

<img src="documentation/screenshots/screenshot-7.PNG">

    3. As a frequent user, I want to be able to book photoshoots.

       1. The home page hero image had a call to action button to "book a shoot!".
       2. The navigation bar clearly shows a About & Enquire page.

<img src="documentation/screenshots/screenshot-1.PNG"> 

### Further Testing

-   The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.
-   The website was viewed on a variety of devices such as Desktop, Laptop, iPhone7, iPhone 8 & iPhoneX.
-   A large amount of testing was done to ensure that all pages were linking correctly.
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Known Bugs

Index jumbotron scroll icon - When hovering over the edges of the icon the color changes to a default dark blue rather than the set hover color.

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/ConnorSargent/FreelancePhotographerWebsite)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
    - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://connorsargent.github.io/FreelancePhotographerWebsite/index.html) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/ConnorSargent/FreelancePhotographerWebsite)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/ConnorSargent/FreelancePhotographerWebsite)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/ConnorSargent/FreelancePhotographerWebsite

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/ConnorSargent/FreelancePhotographerWebsite
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Credits

### Code

-   [Bootstrap4](https://getbootstrap.com/docs/4.4/getting-started/introduction/): Bootstrap Library used throughout the project mainly to make site responsive using the Bootstrap Grid System.

### Content

-   All content was written by the developer.


### Media

- All Images are taken from [Pexels](https://Pexels.com) 

- Creators and links to images:

#### Index Jumbotron
- Mylo Kaye - [Image](https://www.pexels.com/photo/aerial-view-of-city-buildings-6585361/)

#### Latest Jumbotron
- Andrew Neel - [Image](https://www.pexels.com/photo/top-view-photo-of-laptop-near-camera-3178938/)

#### Index Cards
- Josh Hild - [Image](https://www.pexels.com/photo/white-concrete-buildin-3396883/)

- Alexander Drummer - [Image](https://www.pexels.com/photo/photo-studio-with-white-wooden-framed-wall-mirror-134469/)

- Wolfgang - [Image](https://www.pexels.com/photo/photo-of-people-watching-a-concert-2747449/)

#### Latest Cards
- Elijah O'Donnell - [Image](https://www.pexels.com/photo/androgynous-woman-leaning-foot-against-grey-wall-5098976/)

- Wendy Wei - [Image](https://www.pexels.com/photo/musical-band-playing-music-on-stage-with-purple-and-white-lights-1864642/)

- Jayberrytech - [Image](https://www.pexels.com/photo/man-wearing-black-pants-3304802/)

- Yasmine qasem - [Image](https://www.pexels.com/photo/woman-standing-in-front-of-white-wall-2034435/)

- Aldrich - [Image](https://www.pexels.com/photo/woman-in-red-and-white-floral-dress-standing-near-store-5464697/)

#### Urban Gallery
- Cottonbro - [Image1](https://www.pexels.com/photo/man-in-white-long-sleeve-shirt-sitting-beside-woman-in-green-sweater-5037620/)
              [Image2](https://www.pexels.com/photo/man-in-white-crew-neck-t-shirt-and-blue-denim-jeans-sitting-on-red-metal-bench-5037571/)
              [Image3](https://www.pexels.com/photo/person-in-blue-denim-jeans-and-black-and-white-nike-sneakers-5037664/)

- RODNAE Productions - [Image1](https://www.pexels.com/photo/fashion-man-people-woman-5898475/)
                       [Image2](https://www.pexels.com/photo/woman-in-white-jacket-and-black-pants-sitting-on-concrete-floor-5898493/)

#### Studio Gallery
- Andrea Piacquadio - [Image1](https://www.pexels.com/photo/woman-in-knitted-shirt-is-screaming-3765144/)
                      [Image2](https://www.pexels.com/photo/pensive-man-in-brown-coat-holding-his-chin-3785078/)

- mikoto.raw - [Image](https://www.pexels.com/photo/photo-of-woman-holding-her-against-red-background-3328103/)

- Anna Shvets - [Image1](https://www.pexels.com/photo/young-boy-in-jacket-holding-white-flower-pot-3771640/)
                [Image2](https://www.pexels.com/photo/man-with-long-hair-standing-in-studio-during-photo-session-4971015/)

#### Event Gallery
- Giorgio Paradisi - [Image](https://www.pexels.com/photo/people-partying-close-up-photography-2705089/)

- Marc Schulte - [Image](https://www.pexels.com/photo/silhouette-photo-of-people-beside-monitor-2952834/)

- Thibault Trillet - [Image](https://www.pexels.com/photo/singer-singing-on-stage-beside-guitar-player-and-bass-player-167636/)

- Zachary DeBottis - [Image](https://www.pexels.com/photo/man-standing-while-singing-2067677/)

- Mwabonje - [Image](https://www.pexels.com/photo/woman-singing-on-stage-1460037/)

#### About & Enquire

- Stefan Stefancik - [Image](https://www.pexels.com/photo/man-on-gray-shirt-portrait-91227/)



### Acknowledgements

-   My Mentor for continuous helpful feedback.

-   Tutor support at Code Institute for their support.