# Muddy Paws Rescue Centre

---

## Competitor Review

---

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

---

## Purpose and Value

---

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

---

My target audience for Muddy Paws Rescue Centre is going to be families with children, and couples.

### **Families with Kids**

> A family of four is looking to adopt a dog that is good with young children. To do this, they will need to look at the different types and breeds of dogs available on the website before they visit. They will have to bring the children to the Rescue Centre, so they will need to make sure there is a dog they want to see before they go. They also want to look at what age the dogs are, as they want one that is quite young, but doesn't need long walks in the week.

### **Couples**

> A couple in their mid-30s are looking for an active dog. They have a caravan and enjoy travelling the country, so need a dog that likes lots of exercise and isn't likely to run away when nervous. They have plenty of room and would prefer a medium or large sized dog. They live in the countryside, the centre is a 40 minute drive from them. Because of this, they want to be sure there is a dog they'd like to see before making the drive.

<br>

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

## Bugs

---

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

The dog preview section on the home page was particularly difficult to layout. I added the images and text, giving them percentage margins so they would be more responsive, but the text and images were slightly off centre with one another.

I did some research on [W3 Schools](https://www.w3schools.com/css/css_grid.asp) and found information about grids. I wrapped the text and image in a div and put these into a grid with two columns. This gave me the flexibility to space the two dog information cards easily, and will also help when I work on my media queries.
