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

<img width="800px" src="../img/flowchart.jpg">

### Design for my site’s shopping cart
In my design, there's a dedicated shopping cart page where users can adjust product quantities with ease. It resembles the invoice page, offering a preview of selected items and their amounts. The cart, which employs session-based data storage, tracks the user's selections. Modifications to product quantities are straightforward, and once finalized, users can proceed to checkout by clicking on the "Complete Purchase" button, leading to the Invoice page. However, to access this page, users must be logged in or register; otherwise, they are redirected to the login page.

### Using the cart
In my shopping cart system, session management is utilized to meticulously track the quantities of products selected by users. Each type of product is given a unique key for identification, and the quantities are neatly stored in an array. This structured approach not only keeps product choices organized but also ensures they are readily accessible for review and modification. This system enhances user experience by maintaining a clear and concise record of their selections, streamlining the shopping process. For example, the cart might look like this: {Emma: [1, 2, 3], Dan: [4, 5, 6]}. 

### Security concerns
To enhance security, my system incorporates an authentication mechanism using cookies, especially crucial during the shopping process. The server checks for a valid cookie to confirm a user's logged-in status before allowing access to the invoice page. Users without a valid cookie are redirected to the login page. To mitigate cookie vulnerabilities, I'm planning on implementing additional security measures such as using secure, and I'm exploring encryption and frequent validation checks to bolster security further. This multi-layered approach ensures robust protection against unauthorized access.

### Personalization in my UI
Upon successful login, personalization in my UI will be achieved by displaying user-specific information like their name, login status, and number of items in the shopping cart on each page. This can be done using sessions or cookies to store and retrieve user data. For example, after logging in, the user's ID or name can be saved in the session array or a cookie. This information is then used to personalize the UI on each page, ensuring the user feels recognized and the experience feels tailored to them. The implementation will involve retrieving the user's information from the session or cookie and dynamically inserting it into the HTML of each page.

### How I'm approaching Assignment 3 differently than Assignment 2
In Assignment 3, I am focusing on adding enhanced features and complexity compared to Assignment 2. This involves implementing sessions and cookies for user authentication and state management, adding a dynamic shopping cart that allows for multiple products and quantities, and integrating a more advanced checkout process including invoice generation and email functionality. Additionally, I am ensuring a more robust user experience by maintaining the user's state across sessions and offering a personalized UI based on their interactions and choices. The overall design is more user-centric and interactive, with improved navigation and statefulness. I am planning on tackling this by devoting a lot more time to additional research compared to how I completed Assignment 2. A lot of the code I am implementing in Assignment 3 requires me to watch YouTube tutorials, study up on specific JavaScript features, and search for useful example code.
