# Overview

In this challenge you will build the backend of an e-commerce system which allows users to search, add items to their shopping cart, create orders, and checkout successfully.

Given a database in MySQL (Github), you will need to implement the backend.

If you are strong in NodeJS, please do this challenge in NodeJS. We have many customers who need NodeJS backend engineers, and a lot of opportunities to match you quickly for medium to long term projects, if you do exceptional work in this project.

If you are not familiar with NodeJS, please feel free to use other frameworks/languages (PHP, C#, Python, Java, etc.). We have fewer customers interested in full stack engineers skilled in these other technologies, but they still exist and we can match you if you do exceptional work in this project.

Any advanced techniques, tools, frameworks used in the code will also give you bonus points. Please add notes in the readme file so we can easily find and evaluate them.

Our customer companies have very high standards for software engineers, so please do your best possible work here to impress them.


# Getting Started - Important
## Endpoints:
Follow the swagger documentation in this [link](https://backendapi.turing.com/docs/), All endpoints, inputs, and outputs need to be exactly matched this documentation. This is your guide.
## Database:
You must use our Turing database’s data to implement the whole project, but you can modify the structure to fit your advanced implementation if you need.
## Errors:
Use this [link](https://docs.google.com/document/d/1Du-9PZ-9Usgq6tRiWB4_bxXr4F4-Z5ZYT--EdZ14qbc/edit?usp=sharing) to check the list of errors, you need to use these codes and messages.
## Authentication:
The Authentication should use a header param named 'USER-KEY' using Bearer scheme.
Your application needs to return the key preceded by the word 'Bearer' at '/customers' and '/customers/login'.
## Payment:
You should use our Stripe API key 'sk_test_lomdOfxbm7QDgZWvR82UhV6D' to do the charge.
You should send the 'order_id' on metadata property to Stripe.
# Core expectations
1. Project structure: Use best practices for your project structure so it can be scaled easily.
1. Error handling:
  1. Clear error handling flows
  1. Document API errors: Let your API callers know which errors might come in return so they can handle these thoughtfully without crashing.
  1. Use loggers to increase error visibility
1. Functionalities: Work as expected. Precise inputs/outputs. Users can go through flows smoothly. No critical bugs.
1. System Design: Use the most advanced backend architecture as you can.
1. Coding: Clean code with best practices. Good coding style. Good comments. Easy to read, debug, and extend the APIs.
1. Performance:
  1. The API should be able to support a high number of requests with low latency, CPU usage. If you can prove that through APM tools, that’s great.
  1. Use state management and caching techniques.
1. Security: Use best practice to avoid DOS attacks, query injection vulnerabilities, cross-site scripting...
1. Testing: You should add test cases for the main functions of the system.
1. Deployment: Host your solution online and provide the URL.
1. Documentation: Describe the architecture, technologies you use in your documents and readme file (visually with images, diagrams...). Provide clear backend API documentation so other developers can follow and use your APIs easily.
1. Source Code: Please upload your source code on Github, set it private, invite TuringCom as Collaborator, and send the link to us.

# Feature Requirements
1. Users can view all items when entering the website
1. Items are displayed properly based on the selected department and category
1. Users can search items through search box
1. Support paging if we have too many items
1. Users can see item details by selecting a specific item
1. Users can add items to their shopping carts
1. Users can register/login using website custom forms, or social login libraries
1. Users can update personal profiles with shipping addresses and other info
1. Users can checkout with 3rd party payment gateways: Paypal, Stripe. This requirement is mandatory, you must use the related APIs for the payment.
1. Users will get confirmations over emails about their orders
1. Clear unused shopping cart frequently

# Advanced requirements
* The current system can support 100,000 daily active users. How do you design a new system to support 1,000,000 daily active users?
  + Describe your design clearly in the documentation so we can follow your steps
  + Implement backend code + database if possible
* A half of the daily active users comes from United States. How do you design a new system to handle this case?
  + Describe your design clearly in the documentation so we can follow your steps
  + Implement backend code + database if possible

# Design
Please check out the design at [Github](https://github.com/zandoan/turing-backend/tree/master/designs) to have a clearer product vision.

# What to Submit
* Must have: private Github link of the source code, clear documentation about the system architecture and list of APIs (Readme.md), number of hours you spent on the challenge.
* Nice to have: hosted link of your APIs.
