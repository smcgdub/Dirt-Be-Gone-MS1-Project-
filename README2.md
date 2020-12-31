# **Dirt Be Gone - Residential cleaning and handyman services website**

The Dirt Be Gone website was created and built by Stephen Mc Govern. The aim of the website is to provide people who live in the Dublin area with easy online access to a range of residential cleaning and handyman services offered by the Dirt Be Gone company. 

# **Table of contents** 

1. User Experience (UX)
  * 1.1 Target Audience 
2. Features
3. Technologies/Languages Used
4. Testing 
5. Deployment
6. Credits
  * 6.1 Content
  * 6.2 Media
  * 6.3 Code
  * 6.4 Acknowledgements  
7. Contact 
8. Disclaimer 

## **1. User Experience (UX)**

1.1 Target Audience - This website is aimed at anyone who:

* Owns, manages, or rents a residential property in the Dublin area that needs the use of a cleaner, housekeeper or handyman.


### **User Stories:**

I am a home owner and i have a large family, doing the ironing for my 5 children takes up a lot of my time, i would like some help doing this so i can spend more quality time with my family. **(End user goal)** I want to be able to review and enquire about using a weekly housekeeper to do the ironing for my family, and know what this will cost me at an hurly rate. **(Measurement for success would be an incoming enquiry from a customer looking to purchase this service)** 

I am a property manager, i manage a large number of residential properties. A garden fence has blown down during a storm. **(End user goal)** I wish to locate a company that provides handyman services, the rough cost associated with this kind of repair work, and to request a call back from the company so i can schedule a date for the repair to be carried out. **(Measurement for success would be an incoming enquiry from a customer looking to purchase this service)** 

I own a buy to let rental property. My current tenant who has been with me for 3 years is moving out of the property at the end of the month. **(End user goal)** After they move out I need to get the property deep cleaned before i can start advertising it again and holding viewings with new potential tenants. **(Measurement for success would be an incoming enquiry from a customer looking to purchase this service)**

INSERT WIRE FRAMES AS A PDF 

## Features

* Feature 1 (About Us) - Allows any user to read more information on the company, when the were set up, why they were set up and what their mission statement is
* Feature 2 (Cleaning Services) - On this page users can browse all of the services offered by the company and the starting price for each service. They can also click on the service they wish to purchase and then be directed to the contact us form so they can enquire about using this selected service. 
* Feature 3 (Our Promise) - Before purchasing a service from the company potential customers can read this section and know what kind of level of service and standards the company promise to achieve.
* Feature 4 (FAQ's) - Lots of customers will always have a few questions about a product or service before they buy it. By adding this section to the website it allows us the potential customer to see if their question is here, and if so, to have it answered. This means the customer doesn't have to call the office number so it will save staff time answering the same kind of questions over and over again. 
* Feature 5 (Contact us) - Customers can use this section to message the company and select which specific service they are interested in using. 

## **Features Left To Implement**

1. An online booking engine where customers can select the type of service they wish to use, and select the date and time they wish that service to start. 
2. An online payment option so people can make payment for the service they wish to purchase 
3. An invoicing system where the company can email invoices to customers that contains a payment link so they can pay online after the job is completed and payment is due. 
4. A customer account and log in where customers can review all of their account details such as the name on their account, their current address, past services purchases, and any current services running (Example: weekly cleaning service)  

## **3. Technologies/Languages Used**

* [Gitpod](https://www.gitpod.io/) - Is the IDE recommended for Code Institute students and the one i chose to develop this project in.
* [HTML5 - Hypertext Markup Language](https://html.com/html5/#What_is_HTML) - This is the markup language i used for this project.
* [CSS - Cascading Style Sheet](https://en.wikipedia.org/wiki/CSS) - I used CSS to help alter and adjust the presentation of the website to create a pleasant user experience. 
* [Bootstrap](https://getbootstrap.com/) - Bootstrap is the most popular CSS Framework for developing responsive and mobile-first websites. Bootstrap 4 is the version i used for the development of this project.
* [YouTube](https://www.youtube.com/) links - I used a link to a product review that is hosted on YouTube about a product that the company Dirt Be Gone offered to customers.  
* [External Link](https://keysafe.co.uk/c500-keysafe.html#:~:text=The%20Supra%20C500%20coded%20Key,box%2C%20then%20look%20no%20further) to a third party website that has all of the technical details about a product that Dirt Be Gone offers to customers.

## **4. Testing**

### **The NavBar**

Created a Navbar using Bootstrap. I did this because it will allow the site to work on mobile, iPad and desktop and it will easier to set when these points come into play.

* The company logo will be displayed on the left, and the menu items will be populated on the right. 
* I have decided that the NavBar menu will collapse from a list into the dropdown hamburger menu from md screen size and below.
* When i created the navbar the menu items were appearing on the left right next to the main logo, i don't like this look, i pushed them to the right by inserting ml-auto into the following line of code:

`<div class="collapse navbar-collapse" id="navbarNav">`

`<ul class="navbar-nav ml-auto">`

* When the hamburger menu is created and you click on it, the menu items appear on the left hand side, underneath the logo, this doesn't look good so i want them to populated below the hamburger menu itself. To solve this i used developer tools in chrome and highlighted the item im trying to change, its showing as a.nav-link - In my code i have inserted into the li class "ml-auto" (Code below)

`<li class="nav-item active ml-auto">`

This now pushes the items over to the right under the hamburger menu where i wanted it to go. I will do this for every li item in my menu so they all populate on the right.

* I also want the NavBar to stick to the top of the page when people are scrolling up and down the page, this will allow them to navigate easily. To do this i have used the code sticky-top (Code Below) 

`<nav class="navbar navbar-expand-lg sticky-top navbar-light">`

### **The Footer**

Again i have decided to use bootstrap for my footer. I have done this because i want my footer, like the nav bar, to react differently on different screen sizes. I have broken my footer down into 3 columns, left, centre, right. 


## **5. Deployment**

## **6. Credits** 

6.3: Code 

* Majority of the code i used was bootstrap. Their [main documentation](https://getbootstrap.com/docs/5.0/getting-started/introduction/) had lots of great information. 

* I also came across a great bootstrap [cheat sheet](https://hackerthemes.com/bootstrap-cheatsheet/) online which i also used quite a bit. A big thanks to [HackerThemes](https://hackerthemes.com/) for making this available online.

6.4: Acknowledgements

* A big thank you to my mentor Dick Vlaanderen who gave me great feedback on my initial ideas for the project

* Also a huge thankyou to all of the tutor team at Code Institute who were always on hand whenever i needed their support 

* A final big thank you to all of the other students, CI alumni and CI staff who were always willing to help out and advise on the official CI Slack channels 

## **7. Contact**

Feel free to contact me on any of the following channels 
* Slack: 
* [LinkedIn](https://www.linkedin.com/in/stephenmcgovern01/)
* [Email](mailto:stephen_xyz1@hotmail.com)
* [Skype](https://join.skype.com/invite/ndruMu7qVuKZ)

## **8. Disclaimer**

This website and all of its content is for educational purposes only.

>
The aim of the website if to provide any potential customer with: 

* The background of the company and their mission statement 
* The services the company offers along with a guide price for these services 
* To allow potential customers to select a specific service and to contact the company directly and request the use of a service 

On the website people can browse the services offered along with their prices, read testimonials from current and past customers, browse our FAQ section, read the companies mission statement, and also make a request for more information if they wish to use the companies service. 

I myself have owned an Airbnb property rentals business in Dublin for the last 5 years and have always found cleaning companies offer very poor websites for their services.