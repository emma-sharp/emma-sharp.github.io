---
layout: project
type: project
image: img/surfer copy.png
title: "Checkpoint Assignment #3"
date: 2023-12-12
published: true
labels:
  - ITM 352
summary: "Develop a prototype of your entire application that addresses the following points:"
---

<div class="text-center p-4">

</div>

<img width="500px" src="../img/flowchart.jpg">

### 1. Show what each page will look like. The pages do not have to be “functional” but the design should clear. Here is an example PPT prototype
In my design, there's a dedicated shopping cart page where users can adjust product quantities with ease. It resembles the invoice page, offering a preview of selected items and their amounts. The cart, which employs session-based data storage, tracks the user's selections. Modifications to product quantities are straightforward, and once finalized, users can proceed to checkout by clicking on the "Complete Purchase" button, leading to the Invoice page. However, to access this page, users must be logged in or register; otherwise, they are redirected to the login page.


### 2. Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site.
Our shopping cart uses session management to handle product quantities. Each product type is identified by a key, and the quantities selected by users are stored in an array format. This approach ensures that product selections are both well-organized and easily retrievable.


### 3. Provide several examples of using the cart.


### 4. Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.


### 5. How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?


### 6. Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)


### 7. If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?


### 8. How are you approaching Assignment 3 differently than Assignment 2?

