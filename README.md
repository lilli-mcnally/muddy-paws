# Muddy Paws Rescue Centre

_Muddy Paws Rescue Centre is a small organisation that rescues and rehomes dogs of various breeds. This website has been designed to showcase the dogs currently needing a home, as well as inform families and couples of the centres location, contact details and adoption process._

---

## Purpose and Value

### **User goals**

- Find a dog they want to adopt
- Find out information about contacting / visiting the rescue centre
- Find out information about owning a dog

### **Why us**

- We nurse dogs back to health
- We're committed to making sure the home is right for the dog

### **Business goals**

- To get users to visit our Rescue Centre, and adopt a dog
- To inform users of our location
- To get users to let us know in advance which dogs they'd like to meet
- To inform users of our adoption process before they meet a dog
  <br>
  <br>

|                                                               Goal | What does the user need to meet their goal?                                                                                                                |
| -----------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------- |
|                                      Find a dog they want to adopt | Photos and information about the dogs currently being housed in the rescue centre. <br> Information of whether the dogs are vaccinated, neutered, chipped. |
| Find out information about contacting / visiting the rescue centre | An address of the rescue centre so they know where to go. <br> A phone number and email address to contact the centre.                                     |
|                            Find out information about having a dog | Information of how the adoption process works <br> FAQ section for owning and training a dog                                                               |

---

## User Stories

My target audience for Muddy Paws Rescue Centre is going to be families with children, and couples.

### **Families with Kids**

> A family of four is looking to adopt a dog that is good with young children. To do this, they will need to look at the different types and breeds of dogs available on the website before they visit. They will have to bring the children to the Rescue Centre, so they want to make sure there is a dog they want to see before they go. They'd like to find out how to adopt, and what age the dogs are, as they want one that is quite young, but doesn't need long walks in the week.

### **Couples**

> A couple in their mid-30s are looking for an active dog. They have a caravan and enjoy travelling the country, so need a dog that likes lots of exercise and isn't likely to run away when nervous. They have plenty of room and would prefer a medium or large sized dog. They live in the countryside and the centre is a 40 minute drive from them, so they want to secure an appointment before making the journey. Because of distance, they also want to be sure there is a dog they'd like to see before making the drive, and will need to check directions and the centre's exact location.

---

## Competitor Review

I have assessed three different type of competitors for this project. First, [Dogs Trust](https://www.dogstrust.org.uk/) which is a large organisation with several rescue centres around the country. The second is [Birmingham Dogs Home](https://birminghamdogshome.org.uk/), a medium sized local dogs home in Birmingham with two centres. Lastly is the [Freedom of Spirit Trust for Border Collies (FOSTBC)](https://www.fostbc.org.uk/) which is an independent dogs home specifically for Border Collies based in Leeds.

### **Pros**

- Dogs Trust
  - Great use of spacing with text and images. Video on landing page draws the user in
- Birmingham Dogs home
  - Consistent use of circles and handwriting-like fonts to create a more “fun” feeling to the website and adoption process
  - “Find a dog” search fixed to the top of every page
- FOSTBC
  - Lots of pictures to draw the user in
  - Great use of colours - green and white makes the text clear and easy to read

### **Cons**

- Dogs Trust
  - Contact us page - user has to scroll to nearly to bottom for contact information
  - Breadcrumb feature inconsistent - House icon used for Home, but then text used for the rest of the breadcrumb
- FOSTBC
  - Hero image and logo too large - the landing page has no immediate information when opened, but you can't see any images either
  - There is a lot of text and content on each page, users may find this an overload
- Birmingham Dogs home
  - Large pictures and text on homepage make the website look a little crowded

## Objectives

**Using the table and scatter graph below, I have decided that the Muddy Paws Rescue Centre's website will focus on the following three objectives:**

- _Advertise the dogs so users can view before the visit_
- _Give information about the adoption process_
- _Show users where the Rescue Centre is located and it's contact details_

| Objective                                                              | Importance | Viability / Feasibility | Colour |
| ---------------------------------------------------------------------- | :--------: | :---------------------: | :----- |
| Advertise the dogs so users can view before the visit                  |     5      |            4            | Blue   |
| Give advice about owning and training a dog                            |     3      |            2            | Green  |
| Give information about the adoption process                            |     4      |            4            | Orange |
| Show users where the Rescue Centre is located and it's contact details |     4      |            5            | Pink   |
| Ask users to donate to the Rescue Centre                               |     4      |            1            | Purple |
| Total                                                                  |     20     |           16            |

<br>

![Scattergraph of the Objectives, Importance and Viability/Feasibility table](/assets/images/objectives-scatter-graph.PNG "Objectives, Importance and Viability/Feasibility table")

---

## Structure

Structure
In order to structure this information in the most user-friendly way, the website will consist of four pages:

- Homepage
- “Meet the dogs” page
- Contact page
- Submit page (this will mirror the contact page but will display a message that says “Thank you for submitting” instead of the contact form)

---

## Wireframes and Prototypes

I started by creating a basic site map on [Figma](https://www.figma.com/), to get an idea of what pages I wanted to include:

- [Figma Site Map](/assets/images/site-map.png)

Next, I started drafting an idea on [Figma](https://www.figma.com/) of what I wanted on my pages to achieve the [three objectives](#objectives) in the form of a mind map

- [Figma Mind Map](/assets/images/mind-map.PNG)

I created Wireframes using [Balsamiq](https://balsamiq.com/) to get an idea of the best layout for all screen sizes

- [Home Page](/assets/images/home-page.PNG)
- [Meet the Dogs Page](/assets/images/meet-dogs-page.PNG)
- [Contact Page](/assets/images/contact-page.PNG)
- [Submit Page](/assets/images/submit-page.PNG)

Finally, I created a prototype of the Home Page using [Figma](https://www.figma.com/)

- [Prototype Home Page](/assets/images/prototype.PNG)

---

## Fixed Bugs

### **Navigation Element**

I created an unordered list of my navigation elements, and changed the list items' display to “inline-block”. However, the navigation elements were sitting underneath the Logo.

![Navigation element displaying underneath the logo](/assets/images/bugs/nav-bug-issue-1.PNG "Navigation element displaying underneath the logo")

First, I tried adding a position of relative property to the navigation elements. I added a bottom property of 50px, half of the 100px height I had set for the header element, and removed the margin from the unordered list. However, the text didn't seem to be align vertically exactly central.

![Navigation element not vertically aligned](/assets/images/bugs/nav-bug-issue-2.PNG "Navigation element not vertically aligned")

I changed the navigation element position to absolute, and removed the bottom property. I added a top of 0 and width of 100%, and was able to centre the text using margin top and bottom, and changing text-align to center. However, my logo was no longer clickable. Upon opening Developer Tools, I realised the navigation element was now covering the logo and it's anchor, making it unclickable.

![Navigation aligned but logo unclickable](/assets/images/bugs/nav-bug-issue-3.PNG "Navigation aligned but logo unclickable")

I amended the width to 80%, and added a margin to the left and right of 10% to the navigation element, which centered the text but also gave enough space for the logo to be clickable.

![Navigation aligned and logo clickable](/assets/images/bugs/nav-bug-solution.PNG "Navigation aligned and logo clickable")

<br>
  
### **Dog Preview**

The dog preview section on the home page was particularly difficult to layout. I added the images and text, giving them percentage margins so they would be more responsive, but the text and images were slightly off center with one another.

![Dog preview section text and images slightly off center](/assets/images/bugs/dog-preview-issue-1.png "Dog preview section text and images slightly off center")

I did some research on [W3 Schools](https://www.w3schools.com/css/css_grid.asp) and found information about grids. I wrapped the text and image in a div and put these into a grid with two columns. This gave me the flexibility to space the two dog information cards easily, and will also help when I work on my media queries.

![Dog preview section text and images in a grid](/assets/images/bugs/dog-preview-solution.png "Dog preview section text and images in a grid")

<br>

### **About Us**

I added two images to my About Us section, but the full image wasn't showing unless I set the dimensions to take up the whole page. I had created two div elements and given them background images of the two images I wanted to display.

![About us div elements showing small portion of the image](/assets/images/bugs/about-us-issue-1.PNG "About us div elements showing small portion of the image")

Instead, I tried removing the div element and replacing it with an img element instead. This meant the whole image could now be seen and the images were still the same size.

![About us img elements showing full image](/assets/images/bugs/about-us-solution.PNG "About us img elements showing full image")

<br>

### **Dog Information**

I initially added the information about each dog into a paragram element, but found this only wrote the individual points as one long string of text.

![Dog information showing as one long string of text](/assets/images/bugs/dog-info-issue-1.PNG "Dog information showing as one long string of text")

I changed this to two paragraph elements, but had the same issue with two lines being too close together.

![Dog information too close together](/assets/images/bugs/dog-info-issue-2.PNG "Dog information too close together")

I tried adding a margin-left property with a value of 50px. This moved the two pieces of information away from one another. However, the two pieces of information on the right were no longer aligned, due to the varying length of each word.

![Dog information no longer aligned](/assets/images/bugs/dog-info-issue-3.PNG "Dog information no longer aligned")

I decided the best way to align this information to the left, but still have the information across two lines instead of four was to change the paragraph elements to two unordered lists. I added margin to the unordered lists instead, and this pushed the information over but still kept the information aligned vertically. My final issue was that although each box looked great, the different text lengths in different dog information boxes was different.

![Dog information no longer aligned](/assets/images/bugs/dog-info-issue-4.png "Dog information no longer aligned")

I added the float property to both unordered lists, one with the value of left, the other with a value of right. Then I added margin to push both unordered lists of 20px from the parent div. I also gave the parent div a width 100%. This gave even spacing across all dog information boxes.

![Dog information no longer aligned](/assets/images/bugs/dog-info-solution.PNG "Dog information no longer aligned")

### **Bootstrap Input box**

I decided to use Bootstrap to format my form, particularly so that when users input information to the "Name", "Phone number" and "Email Address" input boxes, the form would feedback that the box was complete by outlining green while that box is being written in.

![Bootstrap styling showing green border and shadow](/assets/images/bugs/bootstrap-input-issue-1.PNG "Bootstrap showing green border and shadow")

The issue with calling this Bootstrap was that while the box is in focus, but not completed, it's outlined red. I wanted this to be blue instead, and for the blue and green borders to be more subtle while the box was clicked in. I also wanted to remove the red cross and green tick icons.

![Bootstrap styling showing red borders with red cross](/assets/images/bugs/bootstrap-input-issue-2.PNG "Bootstrap styling showing red borders with red cross")

I tried to adding a border colour to the form-control class but I could only change the border width. Next, I opened Developer Tools and found the properties I needed to edit were under ".form-control.is-invalid, .was-validated .form-control:invalid". I was able to delete the background image property, which removed the cross, and change the border colour. This changed the border colour for when the box was clicked but not yet completed from red to blue. However, it only changed the red border for after you had clicked in and out of it. I still needed to change the colour of the border when the box was clicked.

![Blue border added, but focus box still red](/assets/images/bugs/bootstrap-input-issue-3.PNG "Blue border added, but focus box still red")

Back in Developer Tools, I clicked on the :hov tab and tried clicking :focus. This brought up another style called ".form-control.is-invalid:focus, .was-validated .form-control:invalid:focus", and here I was able to amend the border colour and border shadow colour to a 1px blue, instead of the 2px red.

![Incomplete focus box now showing with blue border and shadow](/assets/images/bugs/bootstrap-input-solution-1.PNG "Incomplete focus box now showing with blue border and shadow")

Finally, I created two more styles but with "valid" instead of "invalid" which amended the green border width and border shadow width to a 1px. I was also able to remove the green tick.

![Completed boxs showing green border and shadow on focus box](/assets/images/bugs/bootstrap-input-solution-2.PNG "Completed boxs showing green border and shadow on focus box")

### **Submit**

On my contact page, I would have liked to have had a message that displayed to let the user know the form has been submitted.

My initial idea was to create a seperate page called "submit.html" where everything would be the same as the contact page, except for the form would be deleted and instead a message read "Thank you for submitting, someone will be in touch with you soon". I've done a lot of research about the Visibility property,and Onclick event but there doesn't seem to be a way to toggle either of these without using Javascript.

I attempted to add the Javascript described in [this example](https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_onclick) by W3 Schools. I wanted to use the button to display this message, however asking the Submit button to both post to the Code Institute Form Dump and change a message visability doesn't seem to be possible.

I spoke to Mitko, my mentor, about this issue and he suggested I change:

`<form class="was-validated" method="post" action="https://formdump.codeinstitute.net/" target="_blank">`

to:

`<form class="was-validated" method="GET" action="thank-you.html">`

This gave the ability to display the thank you page to the user once they've submitted the contact form, but unfortunately doesn't post the form's information anywhere.

### **Navigation Toggler**

I added a Boostrap Navigation bar to my website, which included a Hamburger Toggler menu for tablet and mobile. However, I had an issue with the toggler and the position of the Navigation drop-down menu. When closed, the Toggler was aligned to the right.

![Toggler aligned right](/assets/images/bugs/nav-toggler-issue-1.PNG "Toggler aligned right")

However, when opened the Navigation menu, the Toggler would swap to the left side.

![Toggler aligned left](/assets/images/bugs/nav-toggler-issue-2.PNG "Toggler aligned left")

I used Developer Tools to find the Toggler had a display of "flex" and used Flexbox Editor to find that "justify-content: flex-end" would change the Toggler to sit on the right side. I wanted to move the Navigation Menu a bit closer to the Toggler, as there was quite a gap between them.

![Toggler and Navigation Menu gap](/assets/images/bugs/nav-toggler-issue-3.PNG "Toggler and Navigation Menu gap")

I changed the position to absolute, which brought the Navigation menu higher but move the Toggler lower, so they now overlapped.

![Toggler and Navigation Menu overlap](/assets/images/bugs/nav-toggler-issue-4.PNG "Toggler and Navigation Menu overlap")

I fixed this issue by giving the Toggler a top property of 15px, and a right property of 20px. This put the Toggler in the top right of the Navigation menu.

![Toggler at top right of Navigation Menu](/assets/images/bugs/nav-toggler-solution-1.PNG "Toggler at top right of Navigation Menu")

---

## Unfixed Bugs

There are no unfixed bugs to my knowledge.

---

## Features

As planned in my [structure](#structure) section, I kept the website to four pages:

- Home Page
- Meet the Dogs page
- Contact Page
- Thank You page (previously called the Submit page)

### **Header and Footer**

The Header consists of the Muddy Paws logo, and links to the three pages.This gives an easy to use Hamburger menu for the user. I also added the [Font Awesome](https://fontawesome.com/) icons to each of the menu items:

- A house icon for the "Home Page"
- A pawprint icon for the "Meet the Dogs page"
- A phone icon for the "Contact page"

![Header](/assets/images/features/features-header.png "Header")

The Footer has useful links, including the Meet the Dogs page and Contact Page. It also has links to the "About Us" section on the Home Page, and another to the "How to Adopt" section on the Dogs page. I added links to each of the four social media websites, and a copyright notice at the bottom.

![Footer](/assets/images/features/features-footer.PNG "Footer")

### **Home Page**

This page is divided into several sections: the Hero image, the Dog preview, and the About us Section.

The Hero image sets the tone for the website from when the user clicks on to the website: it's about dogs. I also added a text box to give the user some context that the Rescue Centre is for rehoming all types of dogs.

![Hero Image](/assets/images/features/features-hero-image.PNG "Hero Image")

The Dog Preview has two "Dog Cards" with an image of each dog and some basic information about them. There's also a link to the "Meet the Dogs" page on each card, and underneath the two cards. I wanted this to be near the top of the webpage as this will likely be the first thing people are looking for when they access the website.

![Dog Preview](/assets/images/features/features-dog-preview.PNG "Dog Preview")

The final section is the About Us section. This gives the user information about how the dogs have been looked after since they got to the centre, and about the centre itself.

![About Us](/assets/images/features/features-about-us.PNG "About Us")

### **Meet the Dogs Page**

The "Meet the Dogs page" is seperated into the Dog Card section, and the Adoption section.

The Dog Card section was created to showcase all the dogs currently available for adoption. Each card has well-sized photograph, the dog's name, their basic information such as age and breed, and a tickbox of whether they're suitable for home that already have children, other dogs, or cats. This section also meets the needs of both [user stories](#user-stories):

**Families with Kids**

> ...They will have to bring the children to the Rescue Centre, so they want to make sure there is a dog they want to see before they go...

**Couples**

> ...Because of distance, they also want to be sure there is a dog they'd like to see before making the drive...

The section also achieves the first of my three [objectives](#objectives)

- _Advertise the dogs so users can view before the visit_

![Dog Cards](/assets/images/features/features-dog-card.PNG "Dog Cards")

The second half of the Meet the Dogs page gives information about how the user can adopt a dog, and how the process works. There's a link to the Contact page once a user is happy to start the process, and information about support following adoption. This meets needs of the [user story](#user-stories) for Families with Kids.

**Families with Kids**

> ...They'd like to find out how to adopt...

It also meets my second [objective](#objectives)

- _Give information about the adoption process_

![Adoption](/assets/images/features/features-adoption.PNG "Adoption")

### **Contact Page**

The third page is split into the "Contact form" section and the "Find us" section.

The "Contact form" is an opportunity for users to get in contact with the centre outside of opening hours. It gives the user the chance to give a date that suits them to visit, but also a tickbox section so they can inform the centre of which dogs they'd be interested in meeting. This will be particularly useful to the user story for Couples, so they can check the dog is still available before they make the long drive.

**Couples**

> ...the centre is a 40 minute drive from them...

I've made the "Name", "Phone Number" and "Email Address" boxes mandatory to help the centre get it touch with the user. To make this easier to use for the user, I've added a blue shadow around the box for when it's clicked on, and a green shadow and border once the box is completed. The "Submit" button is a link to the "Thank You Page"

![Contact Form](/assets/images/features/features-contact-form.PNG "Contact Form")

The "Find Us" section contains a Google Maps iframe, so users can see the exact location of the Rescue Centre. There's also the address, phone number, email address, social media links and opening hours. The phone number and email address are anchor elements so the user doesn't have to copy and paste this information. This section meets the [user story](#user-stories) needs for Couples:

**Couples**

> ...and will need to check directions and the centre's exact location.

This section meets my third and final [objective](#objectives)

- _Show users where the Rescue Centre is located and it's contact details_

![Find Us](/assets/images/features/features-find-us.PNG "Find Us")

### **Thank You Page**

The Submit button from the "Contact Page" sends the user through to the "Thank You Page". This page isn't accessible any other way from the website, and it has a small box with feedback that the completed form has been sent to the Rescue Centre. It also has a link back to the Home Page.

![Thank You Page](/assets/images/features/features-thank-you.png "Thank You Page")

### **Future Features**

When I began working on this project, I looked at five potential [objectives](#objectives), but was unable to implement the following two:

- Give advice about owning and training a dog
- Ask users to donate to the Rescue Centre

In the future, I would I would like to add a "Donate" page to this website, and include mention of this on the Home Page. I'd also like to have a page just for FAQs and helpful guides about adopting, owning and training a dog.

---

## Design

### **Colours**

I decided to keep the colouring for this website quite simple. I knew there would be a lot of images of the dogs, and I wanted to make sure the user wasn't overloaded with content and colour, as well as the large images.

The main two colours used are blue and yellow.

![Colours](/assets/images/design/design-colours_50.png "Colours")

I liked the idea of using green at first to represent grass, for all the walks a user would have with their new pet. However, looking further into the psychology of colours I noticed on [Colour Psychology](https://www.colorpsychology.org/blue/), [The Good Trade](https://www.thegoodtrade.com/features/clothing-color-psychology/#:~:text=For%20this%20reason%2C%20wearing%20blue,for%20work%20or%20school%20presentations.) and [Medium](https://medium.com/@bloominari/color-psychology-in-web-design-f60656b8f313#:~:text=Blue,security%2C%20intelligence%2C%20and%20reliability.) that blue may be a more effective colour. These websites say blue is a colour for calmness, but also for loyalty, stability and safety. I liked the connotation of loyalty, to tie in with the natural loyalty most dogs have. I also liked the idea of the user providing the stability and safety a rescue dog needs after a difficult life.

[Colour Psychology](https://www.colorpsychology.org/yellow/) and [The Good Trade](https://www.thegoodtrade.com/features/clothing-color-psychology/#:~:text=For%20this%20reason%2C%20wearing%20blue,for%20work%20or%20school%20presentations.)
also said yellow provokes feelings of hope, positivity and energy. These all fit with the experience of getting a dog, and also ties to the dogs hope of finding a forever home. I also found the happiness from yellow ties well to the happiness we experience when doing something good, such as rescuing an animal.

I decided to use the darkest blue for the boldest features: the Footer, the "See More Dogs" button and the social media links on the contact page.

![See More Dogs button](/assets/images/design/design-blue-button.png "See More Dogs button")

I used the middle blue and lightest blue to create boxes around parts of the website, such as the dog cards, contact form and thank you box.

![Thank you box](/assets/images/features/features-thank-you.png "Thank you box")

I chose the yellow colour the heading of the Dogs Page and Contact Page. I also used it for the hover selected in the footer.

![Yellow heading](/assets/images/design/design-yellow-heading.png "Yellow Heading")

![Yellow hover selector](/assets/images/design/design-yellow-hover.png "Yellow hover selector")

### **Typography**

I decided I wanted to pick a sans-serif font for the typography. I found "Dosis" on [Google Fonts](https://fonts.google.com/) and felt this was a great choice as it's friendly and welcoming to the user.

![Dosis](/assets/images/design/design-font.PNG "Dosis")

### **Imagery**

The Dogs page and Home page both have information about the dogs currently homed at the Rescue Centre, so I added images of each dog happy and sitting in the sun to go with the information.

![Dog image](/assets/images/design/design-dog.PNG "Dog image")

For my Hero Image, I decided to use an image of puppies running on a field. In the "About Us" section, I chose two images for this section; one of a woman walking several dogs in a grassy field, and the other of two vets looking at a dog to see how they could help. I wanted images that showed we've really looked after the dogs up to this point, and that we intend for the user to be the same by making sure the dog they adopt is both healthy and happy.

![Woman walking dogs](/assets/images/design/design-about-walk.PNG "Woman walking dogs")
![Dog being looked at by vets](/assets/images/design/design-about-vet.PNG "Dog being looked at by vets")

### **Styling**

With a lot of images and information about the dogs across the site, I chose to make the website quite spacious.

As the "About Us" section on the Home Page is quite large, the layout of this changes for tablet and mobile screen size. The text also has smaller margins on small mobiles, so it can take up more of the phone screen.

I wanted to make sure the dog cards had plenty of space around them, so I designed the Dogs Page to be in a grid which changes for different screen sizes.

On the contact page, I created the contact form with plenty of spacing around it, and added a background colour and border to contain the form questions and submit button.

![Contact form spacing](/assets/images/design/design-contact-form.PNG "Contact form spacing")

On the second half of the page, I styled the map to take up a large percentage of the screen to give the user as much room as possible to check where the Farm is located, as it's out in the countryside. I gave lots of line spacing to the "How to find us" section, whilst making sure all the information in the box can be seen at once.

I kept the bordering on the text box on the Hero Image consistent with the Contact and Dogs page Headings with a gap inbetween, and which also ties to the logo. Throughout the website I've also added a small border radius to most elements to make the site more welcoming to users.

![Hero Image text](/assets/images/design/design-hero-text.png "Hero Image text")

### **Backgrounds**

Most of the website background is an off-white colour. Each of the dog cards have a slight blue colour, not only to group the information together, but also to tie the dogs to the connotations of the blue: loyalty, stability, safety.

I chose to use an image for the background of the "How do I Adopt" section, which is either a puppy lay on grass, or sandy paw prints depending on the screen width. I partly wanted a background image here to break up the page from the dog card section, and wanted to keep the imagery around dogs. However, I also wanted the footprints to symbolise a potential future for the user with their new best friend.

![Adoption sandy paws image](/assets/images/design/design-adoption.PNG "Adoption sandy paws image")

---

## **Responsiveness**

### **Header and Footer**

- In the Header, I added and adapted the [Bootstrap Navigation](https://getbootstrap.com/docs/4.1/components/card/#navigation) feature for tablet and mobile devices. This gives an easy to use Hamburger menu for the user.
- For the Footer, I had the four internal links change to two columns on tablet sized screen, and one column for mobile.

![Header for tablet and mobile devices](/assets/images/responsiveness/header-tablet-mobile.png "Header for tablet and mobile devices")

![Footer for mobile devices](/assets/images/responsiveness/footer-mobile.PNG "Footer on  mobile devices")

### **Home Page**

- The Hero Image width adjusts to the width of the screen for Desktop and tablet, and on mobile there's a smaller image so more of the puppies are showing.
- The Hero Text div adjusts in width for Desktop and tablet, and for mobile takes up most of the width of the screen so the wording is across two or less lines.
- The Dog Cards stack on top of one another at mobile screen size to give plenty of space for each dog's picture and information
- The About Us section changes to stacked for tablet and mobile. At smallest mobile size, I made the text margins smaller to give the wording more screen space.

![About us on mobile devices](/assets/images/responsiveness/about-mobile.PNG "About us on mobile devices")

### **Dogs Page**

- The Heading adjusts to screen size, with the font size set to 5vw, but at mobile size becomes set at 40px in width to maintain a good size.
- At Desktop size, there are two rows with three dogs on. At tablet size screen, this changes to three columns, with two dogs. Once below tablet size, the dog cards change to six rows, with one dog per row.
  - I kept the sizing of the dog cards consistent, because being able to see the dog is really important to the user. I did feel that having 6 rows in the grid for mobile made the webpage a lot longer. I went back to my [competitors websites](#competitor-review) and used Developer Tools to see how they adjusted their webpages. I found that for mobile devices, all three only showed one dog at a time
- In the "How to Adopt" section, the image for Desktop was quite wide horizontally, so I changed the background image to pawprint in the sand for mobile devices.

![Dog cards on tablet devices](/assets/images/responsiveness/cards-tablet.PNG "Dog cards on tablet devices")

### **Contact Page**

- The Contact Heading adjusts for smaller screens in the exact same way as the Dogs Page heading, as they're both part of the same class.
- The sentence at the top stays central and adjusts in width as screen size becomes smaller.
- The Contact form adjusts width to suit the screen size.
  - Each checkbox and label stays together. Once the screen is smaller than 549px, each dog name and their corresponding checkbox move to the line below as the screen gets smaller.
  - I listed the submit button width as a percentage so it gets smaller with the screen size, but I adjusted the percentage for mobile in comparison to tablet and desktop.
  - I also amended the percentage width of the form itself for largest screens over 1450px as 50% width was excessively big.
- For the Find Us section, I kept the address and contact details together with the opening hours, so that smaller screens didn't lose the ability to have these two important sections together.

![Find us on desktop devices](/assets/images/responsiveness/find-us-desktop.PNG "Find us on desktop devices")
![Find us on tablet devices](/assets/images/responsiveness/find-us-tablet.PNG "Find us on tablet devices")
![Find us on mobile devices](/assets/images/responsiveness/find-us-mobile.png "Find us on mobile devices")

### **Thank You Page**

- The Thank You box is a percentage width that adjusts to the screen width, and the text inside stays centrally aligned whilst also adjusting.

![Thank you message on mobile devices](/assets/images/responsiveness/thank-you-mobile.png "Thank you message on mobile devices")

---

## Deployment

This site was built on Codeanywhere. I've used git add, commit and push to publish it on Github.

To deploy the site, I firstly went logged into Github and opened the Repository. I clicked "Settings" and then selected "Pages" on the left side of the screen.

Then, under "Branch" I chose "Main", and clicked Save.

---

## Manual Testing

All manual testing has been completed and can be accessed using the link below:

- [Manual Testing](test.md)

---

## Digital Testing

| Validators                                                         | Results |
| ------------------------------------------------------------------ | :-----: |
| [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) |    ✓    |
| [W3C Markup Validation Service](https://validator.w3.org/)         |         |

<p>
<a href="http://jigsaw.w3.org/css-validator/check/referer">
    <img style="border:0;width:88px;height:31px"
        src="http://jigsaw.w3.org/css-validator/images/vcss-blue"
        alt="Valid CSS!" />
    </a>
</p>

---

## Credits
