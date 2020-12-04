# Plant Factory 


Mock Up  


Link to Live Website 
https://crypticcaroline.github.io/ms1-plantfactory/index.html

GitHub Repo 




## About 
 Plant Factory is a buisness concept created for my MS1 project with Code Institute.  
 Plant Factory is a buisness dedicated at bringing postive change to workplaces in the form of adding more natural elements. 
 The vast majority of workspaces within the UK do not have any access to natural elements within their workplace.  Having natural elements such as plants can boost postive wellbeing, increase productivity and creat a more appealling place to work. 
 Plant Factory offers both bespoke plant feature building and installant and potted plants/trees of a range of sizes for office place.  Plant factory will visit the buisness in order to asses the sizes needed.  Currently they do not offer plants to be bought online as they are dealing in larger quanities/ larger plants suited to buisnesses. If  a bespoke client Plant Factory will take care of the design and cater for individual requirements. These include large built in plant walls, islands with trees in the middle and hanging fixtures. 
 Plant Factory would need to have a website to help get new clients and also showcase some of their current or existing work.  Plant Factory will need to have contact form so that new and existing clients could reach them easily.   Plant Factory is a small company with a small range of website needs,  there is scope for the buisness to grow.  As the buisness grows the website can be adapted to the growing buisness and additional features implamented. 


## Index – Table of Contents

* User Experience (UX) 
* Features
* Designs 
* Technologies Used
* Testing 
* Known Bugs
* Deployment
* Acknowledgements 

## User Experience (UX)
### User Stories

#### Reasons a user may visit the site
* A user looking for office plants to add to the office or work space or buisness.
* A user looking to install a plant feature.
* A user who already has a quotation but wants to get in contact.
* A user doing research on what we offer.
* A user looking to see if we have done previous work.
* A user showing the site to other people within their buisness.

#### What a user may expect
* Easy to navigate website 
* Good presentation and visually appealling reglardless of screensize.
* Links and functions work in the way expected.
* Information about what Plant Factory does.
* A way to get in contact with Plant Factory.


#### What a user may want
* To be able to find links to social media pages.
* To see examples of previous work carried out.
* To be able to chat with someone online.
* To be able to buy plants online.


#### As a developer / buisness I expect
* To provide information about Plant Factory.
* To provide an easy way for new and existing clients to contact us.
* To showcase some of the work we are proudest of. 
* To provide an easy to navigate website with links that work as expected.
* To showcase customer testimonies and expect customer to read them.
* For clients to be invoked into contacting us for a quote. 



## Designs

### Colour

I have used rich green as my main colour theme for the website. This has been paired with an offwhite colour to ensure good contrast. This will help with Accessibility for visually impaired users. 
This goes with the theme of the website and the buisness.  The buisness moto is making offices greener.  
These colour features several times througout the website which is why I have set a varible in the code.  
I have used the following 

     :root {
    --main-green:#0b720b;
    --off-white:#fdfdfd;
    --dk-brown:#0c0606;
    --md-brown: #2a2020;
     }
    
This means if the buisness decides at any point to change the key colours they can easily change it in the variable so that they don't need to go through and change every colour individually.     
![Colour scheme](README-files/colors.png)

For the rest of the colour scheme I have kept the range of colours to a minimum using only a few additional colours where needed.  I have used a mid brown and dark brown for some text.  This still ties in with the theme of nature but provides a better design. 
Another reason I have chosen not to use black and white is because it is estimated that 20% of the general population has a form of visual stress (significantly higher percentage in those with disorders such as dylexia) which is a processing perception problem. Which can cause issues with processing text and patterns.  Black on white has been shown as one of the most difficult for sufferers of visual stress to read.  

I initially used https://mycolor.space/ to help me narrow down my design choice after using the colour picker on my hero image.  I had already decided to use green but hadnt decided on the exact shade. Although this was helpful in finding colours that worked well I chose to alter the palette to my choosing. 

I have purposely not used any red on the website as this may cause issued for people with a red/green colour defiency.

### Typography 

I have used https://fonts.google.com/ for my fonts.  I have chosen to use Yanone Kaffeesatz as my main font throughout the website.  This is a fairly modern looking style that is easy to read at various sizes.  To incerase it's readabilty I have increased the letter spacing in most cases.  
For the use in the headers I have increased the letter spacing further to make the headings seem more defined and stand out. I have also used a varity of font weights to make some sections easier to read and stand out. 

I have also used Comic Neue for the testimonies this is because the style is a little more playful and is a welcome change from the font used in the main body of the website. 

I imported the following code into the top of my style.css file

        @import url('https://fonts.googleapis.com/css2?family=Yanone+Kaffeesatz:wght@300;400;500;600;700&family=Comic+Neue:ital,wght@0,300;0,400;1,400&display=swap');


### Call to Action

I made all my call to actions as easy to see as possible. 

* The links in the Nav/Logo are highlighted using a change in background colour and text colour when the mouse is hovered over them.
* Request a Quote is styled as a button to be more inviting for the users to click.  I have used a complete colour switch when the mouse is hovered over the link so that the user can clearly see it is a link.
* Submit link on the form and the Contact Us link in the form have also been styled as a button with a complete colour switch.  The colour used are the 2 main colours for consistency and because the change between the colours are easy to see. 
* The Request a Quote in the main body of index.html and the Contact us in the Footer also open up a new tab -  I have done this so that if the user if still reading something on the main page they won't loose their place on the page. 
* The social links will send the user to the companys social media pages.  They also change colour when hovered over.


### Layout 

* I have used responsive design when creating the website as the sight is expanded from a mobile first view point some of the content goes from being stacked to be in adjacent coloumns.  This allows the user to see more of the website on a larger screen. I have also set a Max-Width for the site so on very large screens the content stays neat and is well formatted. 
* I used Bootstraps for the use of the grid system and for the carousel. I used chrome dev tools in the development of the website and altered the column classes in devtools first before implamenting into my code. 
* I have also used a max-width, this is to ensure the content still looks good.  AS this is a Buisness to Buisness company the decisions may not be made by an individual but as a collective.  This means that meetings may take place and the site presented on a larger screen.  The max-width keeps the website looking neat and professional. 
* I have used containers paddings and margins to make sure that the content is not too close together. 

#### Homepage Wire Frame 

![Homepage Wireframe](README-files/homepage.png)

#### Testimonial Wireframe

![Testimonial Wireframe](README-files/testimonialspng)

#### Form Wireframe 

![Form Wireframe](README-files/form.png)





### Imagery   

Seeing as the buisness is a concept I had no images to use from the company. I looked for simple and eye catching designs that mirrored the website ideals when looking for hero images and carousel images. I used a jumbotron for the hero image and I placed an overlay over the top of the carousel. This was to increase the contrast between the imagary and text. 
I used images of people in the testimonals and for the about section.  This was to make the buisness seem friendly and approachable. These images also grow on hover, this is so the user can see the images more clearly. 
I resized some of the images using tiny.png and also cropped and flipped the hero image for use on smaller devices



Image Links - 
* [Hero](https://unsplash.com/photos/x2Tmfd1-SgA)
* [About Image](https://unsplash.com/photos/8FAEyjo3Dek)
* [Testimony Image ](https://unsplash.com/photos/Jnxtlv_Fo14)
* [Testimony Image](https://unsplash.com/photos/HrpYHchKb5Y)
* [Testimony Image](https://unsplash.com/photos/ROJFuWCsfmA)
* [Carousel Images](https://unsplash.com/photos/K86O7q3jddY)
* [Carousel Images](https://unsplash.com/photos/VWcPlbHglYc)
* [Carousel Image ](https://unsplash.com/photos/p_kICQCOM4s)


I also used a pattern back ground of leaves for the form page and the What we offer section.  This was to tie into the theme of the buisness and increase visual appeal. 

[Pattern background](https://www.freepik.com/free-vector/mostera-background_4258347.htm#page=2&query=pattern+background+plant&position=46)


Should the hero or pattern image fail there is a background color set so that the colours of the text can still be read. 
The images in body of the website all have alt attributes.  This is to ensure that screen readers are able to describe the image to the user or if the image fails to load.  This is also to help with ranking of the website. 



### Mock Up


## Features

#### Universal Features Across the Site

###### Logo and Navigation Bar
The Navigation is at the top of the webpage.  The logo and Nav links all change colour and are highlighted when hovered.  The nav links direct the user to the correct page of the site. When the logo is clicked it will take the user back to the home page.
When the page is active the class .text-uppercase is all in Capital letters and a different colour.  By having both these change it helps to improve the accessabilty
When on smaller devices the nav goes underneath the logo and it centered.  For the larger screens the nav is aligned to the right hand side of the page and is on the same line as the Logo.  I used white-space:nowrap to stop the (Request a Quote) from splitting when the size of the screen in lowered. The colour of the nav is our 0ff-white and the text is our main green colour

###### Responsiveness

As the page is scaled up and down for different screen resolutions the content stays neat.  This has been achieved using a mixture of media queries and Bootstraps responsive columns.


###### Accessibility

All images and navigations have an alt attributes or aria-label.  This is to make the site easier to use for people with visual impairments by allowing them to navigate the site easily. 
There is high contrast used throughout the design. Header elements have been use in sequence so that the site makes semantic sense to screen readers. 
With links being consistant when hovered over. 

###### Footer 

The footer split into 3 sections.  Opening Hours, Contact Info and Social. The colour used for the back ground is our main-green colour with a reduce opacity as the colour is very bold when at 100%. Theses are stacked on smaller devices and are arranged in 3 coloumns on larger devices.   

The Opening Hours includes the times the office would be open.  The contact details offer alternative ways of getting in contact with the buisness.  Such as Address, telephone and email.  The last section Social has links to social media sites using Icons from [Font Awesome](https://fontawesome.com/) When hovered over these change from a white colour to a different shade of green than the background. The social section also includes a Contact Us link that is styled as a button to premote contact to Plant Factory.


#### Features Specific to Pages

###### Homepage 
Includes a hero image  reminder of the name of the company (Plant Factory) and a slogan to entice users to continue reading.  
About section with information of what Plant Factory does including an image of the owner.  On smaller devices is stacked, and in 2 columns on larger resolutions.
Benefits sections lists 3 benefits of having more plants in the office.  On smaller devices this is stacked, medium devices has 2 columns and the last benefit is arranged underneath and larger devices is in 3 serperate coloumns. 
What we offer section is displayed stacked on smaller devices and in 2 coloumns on larger screens and offers potential clients the option of potted plants or bespoke features. At the bottom of the option is another link to the contact us form. 

###### Testimonial
Includes a carousel at the top, paired with an overlay for text colour constrast and information of the buisness that the work was carried out for and the type of option they opted chose.  Below the carousel is the testimonies matching the pictures above with a picture of the person giving the testimony.   I have scaled images very large, this is because it is a showcase of the type of work the buisness has carried out.  
I have staggered the testimonies on all devices. 

##### Form 
The Form page consists of the form and universal features only.  
The form includes fields for the user to enter their business name and contact using - input type="text"
The input field for email requires the answer to be an email 
the number has to be a number in order to be valid. 
Prefernces for contact method is by use of a radio button
Options they would like to talk about is a checklist.  This is to make sure when the form is submitted it goes to the correct team.
There is a - textarea - to allow the client to ask any further details.  I have used placeholder text to encourage the user to make any further comments. 

The submit button is large and changes colour when hovered over.

I have set the form to POST with an action of "contact.php" this won't currently go anywhere as github pages is static hosting only. 

The form is stacked for mobile use.  For the larger screens the radio buttons and check list appear inline.
The labels are clear as to what should go in the field and all fields are set to required. 


### Future Features 

* Nav collaspes on mobile
* Has a log in area where clients can chat online with memebers of the team and has the ability to share designs and discuss offers. 
* Has a form submited status to give users peace of mind that the form has been sent correctly and sends the form to Plant Factory email.  
* Create an option for businesses to buy smaller plants online with a way to make online payments. 
	


## Technologies Used 
* HTML5 - Mark up language using semantic structure.
* CCS3 - Casscading style sheet used to style.
* Gitpod.io - for writing the code for the website. Using the command line for commiting and pushing to Git Hub
* GitHub - USed to keep repositive
* GIT - for version control of the project.
* Bootstrap - For responsive design/carousel - overwriten some coe within my own stylesheet
* Google fonts - For styling the typography
* Balsamic wireframe - To build wireframes in the design phase. 
* Font Awesome - for social media icons



## Testing 

Nav links work and the user is directed to the correct page of the site. 
Logo takes the user back to the main page.
Contact us and Request a quote open new tab and takes user to Form.
Hovers over links are clear and not default blue.
Social links works. 
    
    HTML Validator 
    CSS Validator
### Usability Testing
    Friends /slack 

    
### Browser Compatibility
    Tested on Chrome, Firefox, Brave,  Internet Explorer, Microsoft Edge, Safari.
### OS Compatibility
    Tested on iOS , Android 10 and Windows 10.
    Tested for responsivness on Chrome DevTools.
### Performance Testing
    Tested on Developer Tools Lighthouse.

### Testing User Stories
    go through each story what is wanted? 


## Deployment 

The project was deployed to GitHub Pages using the following steps...

Log in to GitHub and locate the GitHub Repository
At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
Scroll down the Settings page until you locate the "GitHub Pages" Section.
Under "Source", click the dropdown called "None" and select "Master Branch".
The page will automatically refresh.
If the page won't load go down to "template" under the "source" and select a template.  I used Jerk & Hyde
Scroll back down through the page to locate the now published site link in the "GitHub Pages" section.

### Forking

Forking the GitHub Repository
By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

Log in to GitHub and locate the GitHub Repository
At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
You should now have a copy of the original repository in your GitHub account.
Making a Local Clone
Log in to GitHub and locate the GitHub Repository
Under the repository name, click "Clone or download".
To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
Open Git Bash
Change the current working directory to the location where you want the cloned directory to be made.
Type git clone, and then paste the URL you copied in Step 3.
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
Press Enter. Your local clone will be created.
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
Click Here to retrieve pictures for some of the buttons and more detailed explanations of the above process.

### Cloning 

Making a Local Clone
Log in to GitHub and locate the GitHub Repository
Under the repository name, click "Clone or download".
To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
Open Git Bash
Change the current working directory to the location where you want the cloned directory to be made.
Type git clone, and then paste the URL you copied in Step 3.
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
Press Enter. Your local clone will be created.
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
Click Here to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Bugs 
* There was an issue with testimonal when the content was view on a phone in landscape mode- FIX I changed the layout of the page so the content would render better. 
* The text on the carousel takes a moment to snap to uppercase.  This is likely because of the delay in reaching the Bootstrap style sheet. FIX written the follow code in directly into my style.css 
         
         .carousel-caption h5, .carousel-caption p {
    color:var(--md-brown);
    font-weight: 600;
    font-size: 1.4rem;
    letter-spacing: 1px;
    text-transform: uppercase;
         }

         
## Credit

Brian - Mentor support and guidence on projects. 

Matt Rudge - Template for gitpod.io 

Bootstrap https://mdbootstrap.com/ carousel used and customised for use in the project. 

[Code Institute SampleREADME](https://github.com/Code-Institute-Solutions/SampleREADME)

Code Institute README Template

W3schools - for various code information

Font Awesome - CDN for icons used in the project

Google Fonts - CDN for fonts used in the project

Images taken from unsplash - see Imagary for links

Freepik - pattern background


### Code :
•	Bootstrap library was used to create a responsive design.
Caroursel taken directly from bootstrap - altered to fit needs 

        <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
            <div class="carousel-item active">
            <img src="..." class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
            <img src="..." class="d-block w-100" alt="...">
            </div>
            <div class="carousel-item">
            <img src="..." class="d-block w-100" alt="...">
            </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
        </a>
        </div>

        
### Content :


Code & Content (not already attributed): Rebecca Kelsall



### Inspiration : 

https://makingmoveslondon.co.uk/benefits-of-plants-in-the-office/   
https://www.plant3r.com/




