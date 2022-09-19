# Salentu: Sule, Mare e Ientu

[Visit the website here](https://etherealsheep.github.io/salento_sole_mare_vento/)

![](docs/images/amiresponsive_image.png)

This site has been created with the idea of providing guidance and inspire people interested in visiting Salento.
Salento is becoming a very popular area all over the world. This website was made for educational purposes only.

This website consists of the following sections:
1. Home
2. Salento Life
3. Must See (A list of places not to be missed)
4. Contact Me (form to sign up to "Salentu, Sule, Mare e Ientu" newsletter)

The business goals for this website are:

1. Provide an idea of what to find if you choose to visit Salento.
2. Inspire people traveling in Salento and encourage tourism.
3. Building a database, a network of contacts with users to send future information and contents.

The user goals of this website are:

1. For the first-time visitor: I want to give you an idea of the best places to visit and encourage trying local, typical food.
2. For the first-time user: I want you to be able to sign up to directly receive content via a newsletter.
3. For the recurring or first-time visitor: I want to find recommendations from a trusted source for seapoints, restaurants/hotels/products based on my first 30 years living in Salento.

---

## **UX**

### **Strategy**

Considering the core UX principles, the first think I did was thinking about the strategy for this website, defining the target users and what features/technologies they would want.

Salentu. Sule, Mare e Ientu target users are:
* Aged 18-60
* People interested in travelling and discover about: culture, history, food, beaches, festivals, music
* Have an interest in visiting South Italy

What these users would be looking for:
* Clear, concise, easy-to-find information
* Beautiful photos that provide inspiration and make the destinations look desirable
* Recommendations about place to visit

This website will offer all of these things whilst also allowing for intuitive navigation and comfortability of use. An effort was taken to not provide an overwhelming amount of information at first glance as this is often the reason people are put off with travel guides.

---

## **Scope**

In order to achieve the desired user & business goals, the following features will be included in this release:

- Header and menu bar, to navigate to various sections of the page
- Brief introduction about meaning of Salento, which is not a real region
- Information about Mediterranean climate and seasons
- Some tips about local food
- List of place to visit primarily
- Gallery of images from my last trip in Salento
- Newsletter sign up form
- Links to affiliate social media pages

---

## **Structure** 

This is a single-page website to allow for desired flow; the navigation bar at the top allows for users to easily move to whatever section of the site they are interested in or they can simply scroll through the information as it is displayed.
I chose the following order for the information:
 'Home > Salento Life > Must See > Contact Me'
this would allow the information to be digested in the best way. There is a concise review of Salento at the beginning before providing some information about the local weather and food. After this, a gallery of pictures is provided to inspire future traveler and encourage old traveler to come back. The last section is a simple sign up form for users to sign up to the Salentu, Sule, Mare e Ientu newsletter.

There are provided two files about the wireframe structure:

- the first is about desktop [Wireframes](docs/Wireframe%20(Desktop).pdf)
- the second is about mobile [Wireframes](docs/Wireframe%20(Mobile).pdf)

---

## **Appearance**

I chose a colour palette based around dark orange.
The reason is because this color give me the feeling of warmth, Salento is a very hot land, and I strongly believe that orange the best color to represent it.
I want this to be helpful for the users to have a sense of what they will get travelling in a warm place like Salento.

---

## **Features**
This is a fully responsive website, it has been designed mobile-first as this is the most likely way it will be viewed; the page consists of four sections listed in the navbar. Where a colour background has been used it has a slightly transparent opacity and the text is white. All of the headings use the font Ubuntu and the body text is Mukta, this consistency has been used across the website to create a coherent design.

### *Navigation Bar*
The navbar is placed on top of a responsive image which acts as a header. The image I have chosen for the header is an iconic building in Salento, Villa Sticchi, is representative of the site's theme and incorporates the color palette, orange, it immediately encourages the user to think of being on holiday.

### *Home*
The purpose of this section is to provide a brief introduction of Salento. It is not a real region of Italy and most likely the user has heard of it but is not sure what it is. A geographical description is provided to clarify this to the user. The main heading is an H2 element followed by more descriptive paragraphs.

### *Salento Life*
This section starts with an H2 heading, which is the section title and it is separated in two parts splitted vertically (two DIV elements).
Each of the two parts has an H3 heading element followed by more descriptive paragraphs, some icons are used for better separation of paragraphs creating a more captivating look.
For these two sections, colors has been choose to be complementary: orange background and white text for the first and white background and orange text for the second.
In the section Salento Life I provided some information about the geography, weather, history and food.

### *Must See*
This section includes a list of place to visit during a short trip, the most iconic and characteristic places to visit. An high contrast with the rest of the webpage was chosento emphasize the importance and capture the attention. To make the images more appealing the image gallery has been created with CSS grid and Fancybox.

### *Contact Me*
This is a signup form that will allow the user to sign up for Salento. Sule, Mare e Ientu newsletter. The form uses 3 elements, 2 text inputs and an email input. They are all required therefore all information is necessary to submit the form. The colour pallet used is to keep consistency with the webpage.

---

## **Technologies Used** 

I have used several technologies that have enabled this design to work:

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
    - Used as the basic building block for the project and to structure the content.
- [CSS](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)
    - Used to style all the web content across the project. 
- [Google Fonts](https://fonts.google.com/)
    - Used to obtain the fonts in the website.
- [Font Awesome](https://fontawesome.com/)
    - Used to obtain icons in the section "The Mediterranean"
- [Google Developer Tools](https://developers.google.com/web/tools/chrome-devtools)
    - Used as a primary method of fixing spacing issues, finding bugs, and testing responsiveness across the project.
- [GitHub](https://github.com/)
    - Used to store code for the project after being pushed.
- [Gitpod](https://www.gitpod.io/)
    - Used as the development environment.
- [Fancybox](https://fancyapps.com/fancybox/3/)
    - Used to format my Salento. Sule, Mare e Ientu photo gallery.
- [Lucidchart](https://www.lucidchart.com/)
    - Used to create Wireframes documents.
- [CSS Formatter](https://www.cleancss.com/)
    - Used to have a better CSS formatted code.
- [W3C Markup Validation Service](https://validator.w3.org/) 
    - Used to validate all HTML code written and used in this webpage.
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/#validate_by_input)
    - Used to validate all CSS code written and used in this webpage.

---

## **Testing**

- I tested the webpage with the following browsers: Chrome, Firefox, Safari, Edge, Opera. It works with all of them.
- I used devtools to test and confirm that this project is responsive, it looks good on all standard screen sizes.
- I tested and confirmed that the different sections are all readable and wasy to understand and navigate.
- I have tested and confirmed that the signup form works well: requires entries in every field and it only accept email in the email field.
The Submit button works.

### **User Stories**

1. **For the first-time visitor: I want to give you an idea of the best places to visit and encourage trying local, typical food.**
As soon as you enter the page you can easily see within the navbar the 'Salento Life' and 'Must See' sections; upon clicking this you are taken to a section filled with tips on various elements.

![](docs/images/salento_life.png)

![](docs/images/must_see.png)

2. **For the first-time user: I want you to be able to sign up to directly receive content via a newsletter.**
The 'Contact Me' button is found in the navigation bar, upon clicking this the user will be taken to this section towards the end of the page. In this section is a newsletter sign up form for the user to register their interest. The form was built using the required attribute so all fields are mandatory.

![](docs/images/contact_me.png)

---

## **Known bugs and fixes**

I did not find any bug during my work.

---

## **Lighthouse**

Lighthouse is a feature of Google Chrome developer tools and is used to assess the performance of the website and its features. I achieved the following result, as you can see below:

For Mobile:

![](docs/images/lighthouse_mobile.png)

For Desktop:

![](docs/images/lighthouse_desktop.png)

---

## **HTML and CSS Validation**

I validated both my HTML and CSS code multiple times whilst building the website. There were 0 errors and 0 warning found. 

HTML validation:

![](docs/images/html_validation_no_errors.png)

CSS validation:

![](docs/images/css_validation_no_errors.png)

---

## **Deployment**

I deployed this website following the below steps:

*GitHub pages deployment* 

1. Log in to GitHub
2. In your Repository section, select the project repository that you want to deploy
3. In the menu located at the top of this section, click 'Settings'
4. Select 'Pages' on the left-hand menu - this is around halfway down
5. In the source section, select branch 'Master' and save
6. The page is then given a site URL which you will see above the source section, it will look like the following: 

![](docs/images/git-pages-published.png)

Please note it can take a while for this link to become fully active. 

*Forking the GitHub Repository*

If you want to make changes to your repository without affecting it, you can make a copy of it by 'Forking' it. This ensures your original repository remains unchanged.

1. Find the relevant GitHub repository
2. In the top right corner of the page, click the Fork button (under your account)
3. Your repository has now been 'Forked' and you have a copy to work on

*Cloning the GitHub Repository*

Cloning your repository will allow you to download a local version of the repository to be worked on. Cloning can also be a great way to backup your work.

1. Find the relevant GitHub repository
2. Press the arrow on the Code button
3. Copy the link that is shown in the drop-down
4. Now open Gitpod & select the directory location where you would like the clone created
5. In the terminal type 'git clone' & then paste the link you copied in GitHub
6. Press enter and your local clone will be created.

---

## **Credits**

The following website were used for research and guidance:

- [Wireframes](https://careerfoundry.com/en/blog/ux-design/wireframing-mobile-apps-websites/)

I used code from the following resources:

- [Responsive Navbar](https://www.w3schools.com/howto/howto_js_topnav_responsive.asp)

- [Image grid](https://www.freecodecamp.org/news/how-to-create-an-image-gallery-with-css-grid-e0f0fd666a5c/)

- [Fancybox gallery](https://fancyapps.com/docs/ui/fancybox/)

The below websites were used for the content: 

- The images in the website has been taken during my last trip in Salento.
- The image in the navigation bar, Villa Sticchi, is the only exception, because it is actually under renovation, I took the image from https://www.italianostra.org/nazionale/a-santa-cesarea-sotto-la-cupola-di-villa-sticchi-si-gioca-la-dura-partita-del-vincolo/

---

## **Acknowledgements**

I would like to thank my course mentor Guido Cecilio for his support and guidance throughout the course of the project, he motivated and inspired me to do better and better.

---