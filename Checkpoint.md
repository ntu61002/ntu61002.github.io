---
layout: essay
type: essay
title: "Checkpoint Assignment #3"
# All dates must be YYYY-MM-DD format!
date: 2023-04-26
published: true
labels:
  - Assignment 3
  - MIS
---

<h1>1. Show what each page will look like. The pages do not have to be "functional but the design should be clear. </h1>
<p>Click <a href = "https://drive.google.com/file/d/1Ewjbn8hqYWPZNGNyZNj0AHg7puNwna7C/view?usp=sharing">here</a> for the screencast.</p>
<h1>2. Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.</h1>
<p>I will integrate the shopping cart in my navbar and it will show many items the user has selected to purchase. Once the user selects the quantity they want for the product they will press the add to cart and when the page is refreshed the amount will show up in the navbar. The user can add and view the cart anytime, but to finish the purchase then the user will need to be logged in. If not, they will be redirected to the log in page where they can sign in or they can register for a new account.</p>
<p>In the shopping cart, the user can add or remove quantities of an item they have selected. The quantity will be limited to the inventory avaliable. The shopping cart will also show a icon of the item so they can decide if they still want that item or not.</p>

<h1>3. Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.</h1>
<p>The items will be stored in the session within an array with each item stored in their respective numerical position. When an item is added to the session the quantity of the item in the session goes up by the amount the user puts in. </p>

<h1>4. How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?</h1>
<p>As of right now, I have my server verfiy whether users are logged in/ registered, if they are not then they cannot purchase products or view their invoice. I still have to work on how to do this by utilizing cookies which will check whether or not the user has one. If the user does not have a cookie, I plan to make it so that they will not be able to checkout. It differs slightly from what I am doing now as I am only checking this through my server.js, login.html, and register.html rather than using cookies. After completing these security concerns, I plan on asking Professor Port for help with encryption. Possible security concerns are that users may still acces the checkout page withtout an account which is why I felt using cookies were integral in solidfying my application’s security. </p>

<h1>5. Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary) </h1>
<p>Once the user has logged in, my application will greet the user with a welcome message by their first and last name. Their is also personalization in the invoice as a thank you message will pop up once they completed the order that will have their name in the message. </p>

<h1>If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?</h1>
<p>I am working alone.</p>

<h1>How are you approaching Assignment 3 differently than Assignment 2?</h1>
<p>I am taking more time to understand the code. Since I just learned about the cookies and sessions I will need to take more time to figuring out how to incorporate them into my code. I've also gotten better at targeting speicfic pages of my website to work on first. For example, the first thing I worked was adding my new products in my products_data.json. I am getting more efficient at finishing my work as I'm not trying to multi-task and do a little bit of my products page then move on to my login page. I learned that this isn't very efficient and will waste more time. This also made me less confused on the code as I will remember what I'm doing rather than jumping around and trying to figure out what each part of my code is. </p>
                                                                           




  
