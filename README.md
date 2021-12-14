# OT Yoga

![Main Mockup](README-files/main-mockup.png)

[Link to Live Website](https://rickofmanc.github.io/old-trafford-yoga/)

[GitHub Repo](https://github.com/RickofManc/old-trafford-yoga)


*** 


## About  

OT Yoga is a newly formed yoga class in Old Trafford, South Manchester. The classes have been established by Marie to guide people on stretching, energising and relaxing as a community. The classes have become popular locally and so Marie would like to leverage this with an online presence where she can communicate to existing students and also increase the number of students attending. As well spreading positivity that yoga can bring into the community, and increase in attendees will help Marie fund the cost of the hiring the venue (which in turn supports other communtiy projects).

ite will allow users of all abilities to access and navigate intuitively to find out when and where the yoga classes are, and which style of yoga will be performed. ![image](https://user-images.githubusercontent.com/91251025/145968384-5da7a474-4191-4d08-a3e7-5819a96b1176.png)



Plant Factory would needs to have a website to tell users a little bit about the business, show potential clients what services they offer and showcase some of their current or existing work. Plant Factory will needs to have a contact form so that new and existing clients can reach them easily. Plant Factory is a small company with a small range of website needs, there is scope for the business to grow. As the business grows the website can be adapted to the growing business and additional features implemented.

***

## Index – Table of Contents

* [User Experience (UX)](#user-experience) 
* [Features](#features)
* [Designs](#designs)
* [Technologies Used](#technologies-used)
* [Testing](#testing)
* [Known Bugs](#known-bugs)
* [Deployment](#deployment)
* [Acknowledgements](#credit)

*** 

## User Experience (UX)

## Strategy
### User Stories  

#### Reasons a user may visit the website
* A user looking for office plants to add to the office or workspace or business.
* A user looking to install a plant feature.
* A user who already has a quotation but wants to get in contact.
* A user doing research on what we offer.
* A user looking to see if we have done previous work.
* A user showing the site to other people within their business.

#### Reasons for the website
* Increase clients
* Showcase work
* Provide a way for new and existing clients to contact us.  

## Scope
#### What a user may expect
* Easy to navigate website 
* Good presentation and visually appealing regardless of screen size.
* Links and functions work as expected.
* Information about what Plant Factory does.
* A way to get in contact with Plant Factory.

#### What a user may want 
* To be able to find links to social media pages.
* To see examples of previous work carried out.
* To be able to chat with someone online.
* To be able to buy plants online.
* How it works - from start to finish.


#### As a developer / business I expect
* To provide information about Plant Factory.
* To provide an easy way for new and existing clients to contact us.
* To showcase some of the work we are proudest of. 
* To provide an easy to navigate website with links that work as expected.
* To showcase customer testimonies and expect customers to read them.
* To encourage clients to contact us for a quote. 

*Note that not all -What the user may wants- will be implamentedimplemented at this step in the buisnessbusiness., Aadditional features may be added as the scope mandate changes and the buisnessbusiness grows.

## Structure
The website will consist of 3 separate pages
* A home page with “About”, “Benefits of plants” and “What we offer” sections. 
* A “Testimonials” page with testimonies and pictures of the work we have previously done.  
* A page with a form to contact the business. 




***



## Designs

## Surface


#### Colour

I have used rich green as my main colour theme for the website. This has been paired with an off-white colour for contrast. This will help with Accessibility for visually impaired users. This goes with the theme of the website and the business. The business moto is making offices greener.  


These colours feature several times throughout the website which is why I have set a variable in the code.


I have used the following 

     :root {
    --main-green:#0b720b;
    --off-white:#fdfdfd;
    --dk-brown:#0c0606;
    --md-brown: #2a2020;
     }
    
This means if the business decides at any point to change the key colours they can easily change it in the variable so that they do not need to go through and change every colour individually.     
![Colour scheme](README-files/colors.png)



For the rest of the colour scheme, I have kept the range of colours to a minimum using only a few additional colours where needed. I have used a mid-brown and dark brown for some text. This still ties in with the theme of nature but provides a better design. Another reason I have chosen not to use black and white is because it is estimated that 20% of the general population has a form of visual stress (significantly higher percentage in those with disorders such as dyslexia). It is a processing perception problem which can cause issues with processing text and patterns. Black on white has been shown as one of the most difficult for sufferers of visual stress to read.


I initially used https://mycolor.space/ to help me narrow down my design choice after using the colour picker on my hero image. I had already decided to use green but hadn’t decided on the exact shade. Although this was helpful in finding colours that worked well, I chose to alter the palette to my choosing.


I have purposely not used any red on the website as this may have cause issues for people with a red/green colour deficiency.


#### Typography 

I have used https://fonts.google.com/ for my fonts.  I have chosen to use Yanone Kaffeesatz as my main font throughout the website.  This is a fairly modern style that is easy to read at various sizes.  To increase the readability, I have increased the letter spacing in most cases.  

For the use in the headers, I have increased the letter spacing further to make the headings more defined and stand out. I have also used a variety of font weights to make some sections easier to read and stand out. 

I have also used Comic Neue for the testimonies. This is because the style is a little more playful and a welcome change from the font used in the main body of the website.


I imported the following code into the top of my style.css file

        @import url('https://fonts.googleapis.com/css2?family=Yanone+Kaffeesatz:wght@300;400;500;600;700&family=Comic+Neue:ital,wght@0,300;0,400;1,400&display=swap');

#### Call to Action

I made all my call to actions as easy to see as possible. 

* The links in the Nav/Logo are highlighted using a change in background colour and text colour when the mouse is hovered over them.
* Request a Quote is styled as a button to be more inviting for the users to click.  I have used a complete colour switch when the mouse is hovered over the link so that the user can clearly see it is a link.
* "Submit link" on the form and the "Contact Us" link in the form have also been styled as a button with a complete colour switch.  The colour used are the 2 main colours for consistency and because the change between the colours is easy to see. 
* The "Request a Quote" in the main body of index.html and the "Contact us" in the Footer which takes them to the form. 
* The social links will send the user to the company's social media pages.  They also change colour when hovered over.

### Imagery   


Seeing as the business is a concept I had no images to use from the company. I looked for simple and eye-catching designs that mirrored the website ideals when looking for hero images and carousel images. I used a jumbotron for the hero image and I placed an overlay over the top of the carousel. This was to increase the contrast between the imagery and text. I used images of people in the testimonials and for the “About” section. This was to make the business seem friendly and approachable. These images also grow when hovered over. This is so the user can see the images more clearly. I resized some of the images using tiny.png and cropped and flipped the hero image for use on smaller devices.


Image Links - 
* [Hero](https://unsplash.com/photos/x2Tmfd1-SgA)
* [About Image](https://unsplash.com/photos/8FAEyjo3Dek)
* [Testimony Image ](https://unsplash.com/photos/Jnxtlv_Fo14)
* [Testimony Image](https://unsplash.com/photos/HrpYHchKb5Y)
* [Testimony Image](https://unsplash.com/photos/ROJFuWCsfmA)
* [Carousel Images](https://unsplash.com/photos/K86O7q3jddY)
* [Carousel Images](https://unsplash.com/photos/VWcPlbHglYc)
* [Carousel Image ](https://unsplash.com/photos/p_kICQCOM4s)

I also used a pattern background of leaves for the "Contact us" page and the "What we Offer" section on the homepage.  This was to tie into the theme of the business and increase visual appeal. 

[Pattern background](https://www.freepik.com/free-vector/mostera-background_4258347.htm#page=2&query=pattern+background+plant&position=46)


Should the hero or pattern image fail there is a background colour set so that the colours of the text can still be read. The images in the body of the website all have "alt" attributes. This is to ensure that screen readers can describe the image to the user or if the image fails to load. This is also to help with the ranking of the website.


***



## Skeleton 


### Layout 

* I have used responsive design when creating the website. as When the page is expanded from a mobile, some of the content goes from being stacked to being in adjacent coloumnscolumns. This allows the user to see more of the website on a larger screen. I have also set a Max-Width for the site so on very large screens the content stays neat and is well formatted.
* I used Bootstraps for the use of the grid system and for the carousel. I used chrome dev tools in the development of the website and altered the column classes in devtools first before implamentingimplementing into my code.
* I have also used a max-width, this is to ensure the content still looks good. As this is a Business-to-Business company the decisions may not be made by an individual but as a collective. This means that meetings may take place and the site presented on a larger screen. The max-width keeps the website looking neat and professional.
* I have used containers, paddings and margins to make sure that the content is not too close together.


#### Homepage Wire Frame 

![Homepage Wireframe](README-files/homepage.png)

#### Testimonial Wireframe

![Testimonial Wireframe](README-files/testimonials.png)

#### Form Wireframe 

![Form Wireframe](README-files/form.png)
 

***


### Mockup

![Mock ups](README-files/mock-ups.png)

***



## Features

#### Universal Features Across the Site

###### Logo and Navigation Bar
The Navigation Bar is at the top of the webpage. The logo and nav links all change colour and are highlighted when hovered over. The nav links direct the user to the correct page of the website. When the logo is clicked on it will take the user to the home page. When the page is active, I used bootstraps class .text-uppercase. This causes all the letters to be capitalized and made the text a different colour. By having both these features accessibility is improved. When on smaller devices the nav goes underneath the logo and it is centred. For the larger screens, the nav is aligned to the right-hand side of the page and is on the same line as the Logo. I used white-space:nowrap to stop the (Request a Quote) from splitting when the size of the screen in lowered. The colour of the nav is our off-white and the text is the main green colour.


###### Responsiveness

The page is scaled up and down for different screen resolutions to help the content stay neat. This has been done using a mixture of media queries and Bootstraps responsive columns.


###### Accessibility

All images and navigations have an alt attributes or aria-label. This is to make the site easier to use for people with visual impairments by allowing them to navigate the site easily. There is high contrast used throughout the design. Header elements have been used in sequence so that the site makes semantic sense to screen readers. Links are consistent when hovered over. I have also set the font to rem so that if someone has their font settings higher for visibility the font size will increase accordingly.


###### Footer 

The footer is split into 3 sections:. “Opening Hours”, “Contact Info” and “Social”. The colour used for the background is our the main-green colour with a reduced opacity as the colour is very bold when at 100%. Theses The three sections are stacked on smaller devices and are arranged in 3 coloumnscolumns on larger devices.


The “Opening Hours” section includes the times the office would is be open. The “Ccontact Ddetails” section offers the user alternative different ways of getting in contact with the business,. sSuch as the business’ aAddress, telephone numbers, and email. The last section “Social” section has links to social media sites using Icons from Font Awesome. When hovered over these links change from a white colour to a different shade of green than the background. The “Ssocial” section also includes a “Contact Us” link that is styled as a button to premotepromote contact to Plant Factory.

##### Meta data


I have included descriptions, author, and keywords into the head element to increase traffic to the website. I have also labelled each page differently so that if the user has multiple tabs open it is easy to recognise each tab.


##### Redirect

I have also included a redirect file so if any of the links don't work or the page does not show up they are redirected back to the homepage. Please see credit for the code used for this function. 

*** 

#### Features Specific to Pages

###### Homepage 
* A hero image reminder of the name of the company (Plant Factory) and a slogan to entice users to continue reading.
* An “About” section with information of what Plant Factory does, including an image of the owner. On smaller devices are stacked, and in 2 columns on larger resolutions.
* A “Benefits sections” listing 3 benefits of having more plants in the office. On smaller devices this is stacked, medium devices have 2 columns, and the last benefit is arranged underneath, and larger devices is in 3 separate columns.
* A “What we offer” section which is displayed stacked on smaller devices and in 2 columns on larger screens. It offers potential clients the option of potted plants or bespoke features. Underneath the option is another link to the “Contact Us” form.

###### Testimonial
* The “Testimonial” page includes a carousel at the top, paired with an overlay for text colour contrast. The carousel gives the user the ability to click on the arrow to go forward or back and also allows the user to change which image is viewed using the buttons on the bottom. I changed the controls on the carousel to invert the colour from the standard white so it would be easier to see. The text includes information about the client and the type of option they opted for. Below the carousel is the testimonies. The testimonies are in relation to the images in the carousel and at the bottom of the text is where each testimony is from. I have scaled the carousel images to be large. This is because it is a showcase of the type of work the business has carried out. 
* I have staggered the testimonies on all devices.
 

###### Form 
* The “Form” page consists of the form and universal features only.
* The form includes fields for the user to enter their business name and contact details using - input type="text"
* The email input field requires the answer to be an email
* The phone number input field must be a number to be valid.
* The preferred contact method is selected using a radio button. This is because there is an option for both contact methods to be selected. By using a radio button errors are avoided that may upset the user.
* Options they would like to talk about is a checklist. This is to ensure the submitted form goes to the correct team.
* There is a - textarea - to allow the user to ask any further details. I have used placeholder text to encourage the user to make any further comments.
* The submit button is large and changes colour when hovered over.
* The form is stacked for mobile use. For the larger screens, the radio buttons and check list appear inline.
* The labels are clear as to what should go in the field and all fields are set to “required”.


I have set the form to POST with an action of "contact.php" this will not currently go anywhere as github pages is static hosting only. 

### Future Features 

* Nav collapses on mobile
* Has a log in area where users can chat online with members of the team and has the ability to share designs and discuss offers.
* Has a “form submitted” status to give users peace of mind that the form has been sent correctly and sends the form to Plant Factory email.
* Create an option for businesses to buy smaller plants online with a way to make online payments.

    

***

## Technologies Used 

* HTML5 - Mark-up language using semantic structure.
* CCS3 - Cascading style sheet used to style.
* Gitpod.io - for writing the code. Using the command line for committing and pushing to Git Hub
* GitHub - Used to host repository 
* GIT - for version control of the project.

Design 
* [Bootstrap](https://getbootstrap.com/) - For responsive design/carousel - overwritten some code within my own stylesheet
* [Google fonts](https://fonts.google.com/) - For styling the typography
* [Balsamiq wireframe](https://balsamiq.com/) - To build wireframes in the design phase. 
* [Font Awesome](https://fontawesome.com/) - for social media icons
* [Beautifer](https://beautifier.io/) - Allowing me beautify my code.
* [Tiny PNG](https://tinypng.com/) – changing some images to smaller sizes

Testing 
* [HTML Validator](https://validator.w3.org/) - Testing validity of HTML
* [CSS Validator](https://validator.w3.org/) -Testing validity of CSS
* [IE NetREnderer](https://netrenderer.com/index.php)
* [Am I Responsive](http://ami.responsivedesign.is/#) - Checking the responsive nature
* [Wave](https://wave.webaim.org/) - Accessibility Testing 
* DEV Tools - Lighthouse

***

## Testing 

* Nav links work and the user is directed to the correct page of the site. 
* Logo takes the user back to the main page.
* Contact us and Request a Quote opens links to Form.
* Hovers over links are clear and not default blue.
* Social links works. 
    
[HTML Validator](https://validator.w3.org/)
![HTML Validator](README-files/html-valid.png)

[CSS Validator](https://validator.w3.org/)
![HTML Validator](README-files/css-valid.png)


A few warnings were displayed when using the validator this is because of the variblesvariables I have used to help with the maintenencemaintenance of the site. The other error is due to the useing of external style sheets. I am happy with the outcome of this test.


### Usability Testing

I sent the project to a few of my peers in the slack community and to a few friends within the industry.  I had them check to ensure all links were working and the website was responsive at different screen resolutions.
One of my friends viewed the project in simplified mode and commented that the website was still easy to navigate and displayed clearly. 


I wanted to carry out Accessibility Testing on the website.  I used [Wave](https://wave.webaim.org/) This was to check to make sure the website the website would work well with screen readers.  I also manually checked the web site by increased the REM settings on my browser and making sure that the content was still visible.  This highlighted a BUG which was FIXED prior to deployment. 

    
### Browser Compatibility

Tested on Chrome, Firefox, Brave, Internet Explorer, Microsoft Edge, Safari.
I tested on older version of Internet Explorer, the website works from Internet Explore 9 and onwards, although not all the content is as designed the overall layout means the content is still easy to read and the images are still visible. 
I used [IE NetREnderer](https://netrenderer.com/index.php) to test the older versions. 

### OS Compatibility
Tested on iOS, Android 10, and Windows 10. - I asked a friend with an IPhone to test that it was working.  
Tested for responsiveness using Chrome DevTools.

### Performance Testing
Tested on the Developer Tools Lighthouse.  This was the first time running through Lighthouse

![Lighthouse results](README-files/lighthouse-before.png)

I made some changes, such as increasing contrast, adding meta data and making sure my HTML was semantic and this was the results.

![Lighthouse results](README-files/lighthouse-after.png)

### Testing User Stories

* ###### A user looking for office plants to add to the office or workspace or business. 
The user can find the information quickly on the first page of the site. The user is given the option to get in contact with us and can have a look at testimonies and images of work carried out.


*** 


## Deployment 

This project was deployed with the following steps

1. Logged into [my GitHub repository](https://github.com/RickofManc/old-trafford-yoga)
1. Clicked on the "Settings" button in the main Repository menu.
1. Clicked "Pages" from the left hand side navigation menu.
1. Within the Source section, clicked the "Branch" button and changed from 'None' to 'Main' in the dropdown menu.
1. The page automatically refreshed with a url displayed.
1. Tested the link by clicking on the url.

### Known Bugs 
* BUG


***


## Credits

* Mentor Brian Macharia for guiding and advising throughoutout the projects lifecycle.
* [Balsamiq](https://balsamiq.com/) - Used to build wireframes in the Skelton phase. 
* [Google fonts](https://fonts.google.com/) - For Roboto, the free family font used throughout the site.
* [Font Awesome](https://fontawesome.com/) - Free social media icons sourced from FA.
* [Pexels](https://pexels.com/) - Free images sourced from Pexels.
* [RawPixel](https://rawpixel.com/) - Free images sourced from Pexels.
* [W3schools](https://www.w3schools.com/) - Source of 'How to...' information throughout the build.
* [Stack Overflow](https://stackoverflow.com/questions/42199911/how-can-i-reorder-html-using-media-queries) - Source of information on reordering HTML when using media queries.
* [HTML Validator](https://validator.w3.org/) - For validating HMTL code, no errors found.
* [CSS Validator](https://validator.w3.org/) - For validating CSS code, no errors found.
* [Anna Greaves README Template](https://github.com/Code-Institute-Solutions/readme-template#love-running) - Source of information for README content and layout.
* Rebecca Kelsall README Template](https://github.com/crypticCaroline/ms1-plantfactory#readme) - Source of information for README content and layout.


### Code

* [FAQs Verical Accordian](https://codepen.io/frogmcw/pen/deqRwa) - Monica Wheeler's code for a Vertcial Accordian in HTML & CSS only.
* [Collapsing Nav Menu](https://codepen.io/kevinpowell/pen/jxppmr) - Kevin Powell's code for creating a collapsable Navigation menu for mobile devices in HTML & CSS only.


### Content

* [Indian Yoga Association](https://www.indianyogaassociation.com/) - Source of information on yoga benefits and qualifications.
* [TriYoga](https://triyoga.co.uk/faqs/) - Source of information on yoga classes and general FAQs.


### Inspiration

* [Convince & Convert](https://www.convinceandconvert.com/digital-marketing/accessible-website-examples/) - Source of inspiration on design and features that improve accessibility which was key in reaching as many people in the Old Trafford community.
