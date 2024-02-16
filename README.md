# CC Ghost Tours

This is a visual online presence for Cork City Ghost Tour.
The target audience would be individual and families interested in a cultural and fun haunted tour of 18th century Cork city. Families from the area and also families visiting Cork as tourists, seeking family-friendly activities that provide cultural and historical insights.
CC Ghost Tour will provide information on the type of ghost tours on offer, who will provide the tours, where it will take place and how to get in contact to book a tour. 

![Image showing screenshots on different size screens](documentation/images/am-i-responsive.png)

## UX

__Wireframe and Prototype__

The tool Figma was used for the Wireframe and Prototype. You can view my [figma page here](https://www.figma.com/file/wqDQe6D5A4Dp42Iwlw0dXI/PROJECT-1-CORK-CITY-GHOST-TOURS?type=design&node-id=0-1&mode=design&t=72VgxDbLXxjmPx43-0)

![Figma Wireframe](documentation/images/Figma-Wireframe.png)

__Responsive Design__

-This website is a mobile-first design. At the planning stage, emphasis was put into the design of a mobile website first, followed by up-scaling for larger devices.
-To achieve this, I used a component-based approach. The Hero, Tour and Guide sections are cards. The cards contain an image on the left and text on the right. These cards or blocks of content can float horizontally on desktops or vertically with flex box on a mobile. Components are considered good UI design as they can be used again on other sections of the project.

__Mapping__

-Looking through other website designs, I chose to go with a two page layout. On the home page, all the information regarding the tour is available and broken up in bite size pieces, so the user wouldn’t feel overwhelmed. This common scroll design will be intuitive and will make the user feel at ease. 
-At the end of the page after gathering the information, the user sees a call to action, a “book now” button. At this stage, the user would have all the information they needed to know if they’ll like to book. 
-The “book” page was separated, so the user would feel that they’re taking the next step, feeling empowered in their decision. 
-This "book" page contains a form centred on the page. The form itself was designed to be responsive. On mobile devices the input fields are vertically places, one over another. On larger devices, a media query was added. The “First name” and “Last name” inputs are placed side by side. As are the “Email address & Phone number” input fields. As larger devices are landscape in view, this design utilises the space more effectively.

__Colours & Font__

-The colour palette is made up of blues, greens and complemented with orange. A split complementary scheme, in desaturated tones to give a relaxed feeling that is pleasing to the eye.
-The use of white text on the darker values/tones and dark grey text on lighter values, means the text is easy is read.   
-The Font used is Roboto and a websafe sans-serif font.
-A Dark grey colour (#4b4b4b) was used on the majority of the text. The hero section uses an off white colour (whitesmoke) to help it stand out from the other text. By doing this, the user will see straight away the most important information.


## Features 


In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Existing Features

- __Navigation Bar__

  - Featured on all three pages, the full responsive navigation bar includes links to the Logo, Home page, Gallery and Sign Up page and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Nav bar](documentation/images/header.png)

-__Button & links__

  - The button was designed to stand out, to be easily visible from the rest of the page.
  - The orange colour is in contrast as it is a complementary colour to the blue and green on the page. 
  - The image below shows the button without hover on the left and with hover on the right. As you can see, the gradient changes direction and the buttons sides expand. 
  - This subtle change is a visual cue that is in keeping with the use of gradients throughout the website.

![button](documentation/images/btn_and_btn.hover.png)

  - 

- __The landing page image__

  - The landing includes a photograph with text overlay to allow the user to see exactly which location this site would be applicable to. 
  - This section introduces the user to Love Running with an eye catching animation to grab their attention

![Landing page](documentation/images/main-page.png)

- __Tour Description__

  - The tour description section will allow the user to see that this is a fun, entertaining tour, presented by knowledgeable, comedic guides that has a strong Cork manner.
  - The "meet your guides" section will give a better insight into two of the companies guides.

![Tour Description](documentation/images/Tour-Description.png)

  - The Route section, will emphasis that this is an 18th century period tour. Giving the user a visual idea of the layout of the city

![Route on 18th century map](documentation/images/Route-on-18th-century-map.png)

- __Call to Action__

The last section on the main page is the "Get in Touch" or call to action.
It gives a prompt to "Get in Touch" and contains a "Book Now" button.
As described earlier in the mapping paragraph, this button empowers the user as it is moving them forward.

![Call to Action](documentation/images/Get-in-Touch-section.png)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for CC Ghost Tour. The links will open to a new tab, allowing easy navigation for the user. 
  - These well know icons/logos are familiar to the user and encourages them to see more on those platforms.

![Footer](documentation/images/footer.png)

- __Book Page__

  - This page will allow the user to send contact details in order to make a booking. This form asks for the following: 
  - 1. First Name 2. Last name 3. Email Address 4. Phone number 5. Booking Date & 6. Your message. 
  - All fields are required and a valid email address (including @,) needs to be entered.
  - After filling in all the required forms, the user will be prompted to submit the form with the “Send” button.

![Book](documentation/images/Form.png)

### Features Left to Implement

- I'd like to introduce a hover page. It will display after clicking the form submit button, to indicate the form was sent successfully.

### Testing 

- HTML
  - No errors were returned when passing through the official [W3C Validator] (https://validator.w3.org/nu/?doc=https%3A%2F%2Fandrewodwyer.github.io%2FCork-City-Ghost-Tours%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) Validator] (https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fandrewodwyer.github.io%2FCork-City-Ghost-Tours%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
- Accessibility
  - The colour and font used make it very easy to read the text while still pleasing to the eye.
  - I used Lighthouse in DevTools to confirm that every page scores well for accessibility.
![lighthouse score](documentation/images/lighthouse-score.png)

#### Browser Testing

  -The site has been tested on the following browsers: Chrome, Safari, firefox & Edge. The layout and functionality was consistent throughout the testing. links, navigation and form submit all work as intended.

#### Manual testing

  Actions and results. 
  -On click, CC Ghost Tour text/logo brings you to the home page.
  -Navbar buttons: when clicked, they take you to different sections or pages. 
  -Book/submit button: when clicked, it will show the code institute form submitted
  -Name, email, phone, date & your message inputs are all required on the form in booking page: If not filled out correctly, it prompt user to do so before allowing them to submit the form. 
  -Social link icons (X, instagram, facebook, you-tube): when clicked, opens pages for those particular social networks.
  All work correctly.

### Unfixed Bugs

There are no unfixed bus.

## Deployment

Log in to GitHub and select CC ghost tour repository.
From this repository, navigate to "Settings" (This is at the top of the page).
when in settings, navigate to pages from the left-hand menu.
In source select “Deploy from a Branch” in the drop down menu.
In branch select “main”. The folder next to it will be “/(root)”
At this point you click “Save”
Your site is now being deployed.
After several minutes the site was deployed.
A link to the deployed site is at the top of this page, click “Visit site”
Alternatively, To get access to the deployed site, click on the “Code” tab of the repository.
On the right-hand side under “environments” click on “GitHub-pages”
In the newly opened pages, click on “view deployment”
[live site](https://andrewodwyer.github.io/Cork-City-Ghost-Tours/)


## Credits 

Code-institute:
The navigation bar and footer originally code was originally sourced from the Love Running Project at Code Institute. The form on the booking Page was also inspired by the Love Running project. However, none of these remain in their original form. Additional code was added to css and html.
W3schools: 
I used w3schools to plan the button and button:hover css layout & colour.
[button css] (https://www.w3schools.com/css/tryit.asp?filename=trycss_buttons_hover)
Semantic elements like section, div etc
[Semantic](https://www.w3schools.com/html/html5_semantic_elements.asp)
HubSpot:
[Tutorial on Git & Github] (https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)
Stackoverflow:
I got a better understanding of flexbox from stackoverflow.
[setting distance in flex](https://stackoverflow.com/questions/20626685/how-do-i-set-distance-between-flexbox-items)



### Content 

- The text for the Home page was written by the developer, Andrew O'Dwyer.
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- Favicon: from icons8.com https://icons8.com/icons/set/favicon-ghost I was able to get a stock ghost icon and change the colours to suit my colour palette.


### Media

- The images used on the home page are AI generated in bing, powered by chatgpt Dall-e. https://www.bing.com/images/create/?ref=hn
- The 18th century map used for the booking page was taken from https://www.linkedin.com/pulse/corporation-cork-city-ireland-agreed-make-provision-scheme-holohan
- These images were then resized using https://imageresizer.com/