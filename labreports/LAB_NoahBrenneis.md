# Lab Report: Requirements
___
**Course:** CIS 411, Spring 2021  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Noah Brenneis  
**GitHub Handle:** NoahBrenneis  
**Repository:** NoahBrenneis/cis411_lab0_req  
___

## 1. Overview

![use case diagram](/assets/Food%20Delivery%20UCD.svg)

In this scenario, the customer, who is a student at a university, is able to order food from the campus's on-site food services and have it delivered to somewhere on campus.

Besides the web server needed to run the service, there are three types of people involved: the customer who orders the food, the cook who prepares it, and the delivery person who brings it to the customer. In addition, the customer's bank account is used as a means of payment.

The customer's primary action is to place an order, which has four steps: selecting the food items to purchase, indicating the on-campus delivery location, adding the needed payment info, and processing the order. The cook then receives the order and prepares it, at which point it is made ready for pickup by the delivery person. This delivery person will then deliver the order to the location specified by the order, at which point the customer receives it and the process is finished.

## 2. Requirements

### Business Requirements
- B.1 - The system must only allow orders to be placed if there are a sufficient number of delivery workers capable of making deliveries (My Younger Brother)
- B.2 - The system must allow for refunds for situations where a placed order is cancelled (Frugal Student)
### User Requirements
- U.1 - The user must be able to store their payment information, allowing them to automatically enter it in future transactions (My Younger Brother)
- U.2 - The user must be able to enter a payment method, delivery time and location at checkout (My Sister)
### Functional Requirements
- F.1 - The system must allow for multiple different items to be ordered at once using a cart system (My Sister)
- F.2 - The system must send users an order confirmation message, either through a connected email or phone number (My Sister)
- F.3 - The system must allow for users to provide confirmation that their orders were properly delivered (My Sister)
- F.4 - The system must provide an order status to the user, displaying the progress of their order (My Younger Brother)
### Non-Functional Requirements
- N.1 - The menu used by the system must provide allergen information (My Sister)
- N.2 - The system must only be usable by students on the campus (Concerned Professor)
### System Requirements
- S.1 - The service must have a website with which the user can place orders and provide payment (My Younger Brother)
- S.2 - A server must be used to store the possible food items, track orders, and remember payment information (My Younger Brother)
- S.3 - The system must utilize the university's student account system to allow students to log in and place orders using them (My Sister)

## 3. Assumptions
This is an optional section, where system constraints, out of scope features or other caveats can be clearly documented.  

Users of this system are expected to use a personal computer or mobile device, and as such the system is expected to be able to run on commonly used devices.

Because universities are not open during certain periods of the year, the service is not expected to function during those periods.

## Appendix: GitHub Notes

### A.1 Forked Repository

![fork relationship diagram](/assets/Fork%20Relationship.svg)

### A.2 Git Logs

Log from Step 2.7:
``` json
$ git log --oneline
8a0c27c (HEAD -> labreports, origin/labreports) Added name, github handle and repo URL to the heading of the lab report.
3c46adc Made a copy of the lab template provided by @trevordbunch.
50d40f8 (upstream/main, origin/main, origin/HEAD, main) Update references to main branch
ef962b1 Fix links in resource area
237b52e Update Instructions for template file
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
fd13d03 initial draft
ad87871 Create License
```

Log from Step 6.4:
``` json
$ git log --oneline
c10cee7 (HEAD -> main, origin/labreports, labreports) Completed the overview, requirements and assumptions sections of the lab report
016a207 Added Food Delivery UCD.svg
3c93519 Added the branch relationship diagram to the lab report
5089d62 Added Branch Relationship.svg
49e18cd Added the fork relationship diagram to the lab report
31a76b8 Added Fork Relationship.svg
841fa45 Added the log of the previous push to the lab report.
8a0c27c Added name, github handle and repo URL to the heading of the lab report.
3c46adc Made a copy of the lab template provided by @trevordbunch.
50d40f8 (upstream/main, origin/main, origin/HEAD) Update references to main branch
ef962b1 Fix links in resource area
237b52e Update Instructions for template file
dafaf5e Merge pull request #2 from NedacNostrebor/patch-1
6293806 Merge pull request #1 from mcjo163/main
7482f04 Typo in lab instructions
3080719 typo in readme
33efb41 formatted template
fd13d03 initial draft
ad87871 Create License
```

### A.3 Branch Repository

![branch relationship diagram](/assets/Branch%20Relationship.svg)