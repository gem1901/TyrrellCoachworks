# Tyrrell Coachworks
Tyrrell Coachworks is a custom metal fabrication business and the purpose of this site is to provide a simple method of contact to potential customers and to showcase the range of metal work they offer.

## UX
From the substantial following Tyrrell Coachworks has on their social media accounts, the profile of their customer base is very clear 99% male with more than half of those in the 55yrs+ bracket. Of these a significant number would have only basic computer skills and for that reason the layout and design of this site has been planned with that demographic in mind.
### User Stories
1. As a visitor, I want to easily understand the type of work Tyrrell Coachworks provide, so I may decide whether they are the business I need.
2. As a visitor, I want to be able to easily find their contact information, so I may get in contact about a project I have.
4. As a visitor, I want to see testimonials from previous customers about the quality of work they received from Tyrrell Coachworks, so I may decide if they provide a good quality service.
1. As a visitor, I want to browse images of the various projects undertaken by Tyrrell Coachworks, so I may see if they experience in the kind of metal work I am looking for.
### The 5 planes of UX
1. Strategy;
The business has three specific goals to achieve from this site:
* To provide a method of contact for potential customers.
* To showcase the wide variety of custom metal work they provide through images and customer testimonials.
* To grow their social media following by providing links to their facebook and instagram accounts.
2. Scope;
To achieve both the business goals and user needs the following features are required:
* Contact form for visitors to submit their information.
* Links to social media accounts on each page of site.
* Image gallery
3. Structure;
Given the customer profile for Tyrrell Coachworks the structure should be simple and uncluttered, allowing the user to easily find the information they require.
4. Skeleton;
Ease of site navigation is paramount to achieve user goals, nav bar must be clearly visible on all pages indicating to the user where on the site they currrently are.
5. Surface;
Typography used must be suitable to audience making it easily read and the use of color should both be appealing to the user but also can be used to make important elements such as nav bar stand out.
### Wireframes
* Website wireframes [view](https://github.com/gem1901/ms1-tyrrell-coachworks/blob/master/assets/wireframes/TCwireframes.pdf)
(Note: Site originally planned with 4 site pages however after taking advice from mentor, reduced to just two pages with gallery and testimonials added to home page instead.)
## Features
- Site is responsive on all devices(details of testing below) ,all internal links working and external links (social media accounts) open in a new tab.
- Interactive elements 

#### Features left to implement 
- Contact form, back end to be set up to receive data using Javascript
- Once more images are obtained the gallery to be further developed into categories for the different types of metal work Tyrrell Coachworks provides.
- Video content to be created for site, 360 walk arounds of vehicles etc.

## Technologies Used
### Languages
-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/CSS)
-   [Javascript](https://www.javascript.com/)
### Frameworks, programs and libraries 
-   [Bootstrap was used for responsive design elements and styling of site](https://getbootstrap.com/docs/4.3/getting-started/introduction/)
-   [Fontawesome was used to add icons to site like social media links](https://fontawesome.com/start)
-   [Google fonts were used to create a custom Typography for the site](https://fonts.google.com/)
-   [Git was used for version control by using the terminal to commit to git and push to github](https://git-scm.com/)
-   [Github was used to store the projects code after pushing from git](https://github.com/)
-   [Balsamiq was used to create wireframes for the site in the design process](https://balsamiq.com/wireframes/?gclid=Cj0KCQiA1KiBBhCcARIsAPWqoSoj-e82t1iFiEmWYmHTNYMSBT8OLneMDOTTAL0S2omCsT7i2NtGn6waAtsLEALw_wcB)


## Testing
- The website was tested on google chrome, safari and internet explorer
- Tested on all my apple devices (Iphone 11, Macbook pro, Ipad air)
- Family who are android users tested site on andriod mobiles and also tablet devices
- Tested using google dev tools 
- All site links were tested on multiple different devices and no issue with any found

### Testing user stories from UX section:
1. As a visitor, I want to easily understand the type of work Tyrrell Coachworks provide, so I may decide whether they are the business I need.
- Upon landing on the site the business name and site navigation are immediately visible. Underneath which is a hero image showing a metal worker at an English wheel, the cover text on this image tells we where the business is based, what type of service they provide and that they can also ship internationally. [Screenshot of mobile home page](https://github.com/gem1901/ms1-tyrrell-coachworks/blob/master/assets/screenshots/mobile-homepage.png)
2. As a visitor, I want to be able to easily find their contact information, so I may get in contact about a project I have.
- On the home page the cover text over the hero image also immediately provides a phone number to contact without having to search through the site, the nav bar also gives me the option of going to the contact us page where I can fill out a form and they will get back to me within 1 working day or if I prefer phone and email details are provided as well as links to their social media accounts. At the bottom of each page in the footer I can also easily find both a phone number and links to social accounts. I have a variety of options to contact Tyrrell Coachworks and they are all easily found.[Contact form](https://github.com/gem1901/ms1-tyrrell-coachworks/blob/master/assets/screenshots/contact-form.png)
4. As a visitor, I want to see testimonials from previous customers about the quality of work they received from Tyrrell Coachworks, so I may decide if they provide a good quality service.
- Easily found on the home page underneath the gallery I can read numerous customer recommendations detailing the high level of skill and service provided by Tyrrell Coachworks.[Screenshot of gallery/testimonial sections](https://github.com/gem1901/ms1-tyrrell-coachworks/blob/master/assets/screenshots/gallery-testimonials.png)
1. As a visitor, I want to browse images of the various projects undertaken by Tyrrell Coachworks, so I may see if they experience in the kind of metal work I am looking for.
- A gallery carousel is provided on the homepage showcasing a variety of different projects, I can also see from the images the custom built tooling they use like they're own English wheel giving me a good indication of the level of craftmanship and expertise.

### Known bugs
- Using google dev tools, testing the Ipad Pro display a white space appears below the footer on the contact page
- Using the W3C validator an error is creating from the <article> tag used in the page structure, this was used to keep the footer at the bottom of the page. 

## Deployment
I deployed the site with my mentor by following the below steps:
1. Log in to GitHub and go to the project repository
2. At the top of the repository click the settings button
3. Scroll down to the github pages section
4. From the dropdwon menu select the master branch to enable github pages for master branch
5. The link for the published site can now be found in the github pages section 

## Credits
- How to fill hero image came from this post:(https://stackoverflow.com/questions/11757537/css-image-size-how-to-fill-but-not-stretch/29103071#29103071
)
- How to get footer to stick to bottom of page came from this post: (https://dev.to/domysee/keeping-the-footer-at-the-bottom-with-css-flexbox-5h5f)
- How to format image carousel came from this post: (https://www.w3schools.com/bootstrap/bootstrap_carousel.asp
)
- How to match exact css color from hero image for site color, I used:(https://imagecolorpicker.com/en) 
### Content
- All content was written by myself the developer
- Customer testimonials consent given by each customer 
### Media
- All images used are my own property
### Acknowledgements
- My mentor for all his help and guidance 
- Tutor support and student care for always being there at any time I needed them