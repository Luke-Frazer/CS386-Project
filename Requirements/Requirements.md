# Requirements

Group 6 - MyGroceryAssistant

Date - February 3, 2022

Group Members - Connor, Luke, Jack, Justin, Jonny, Nick

## 1. Positioning

### 1.1. Problem Statement
The problem of unorganized/unoptimized grocery shopping affects everyone who has ever shopped for groceries;
the impact of which can cost you finically as well as waste time with extra grocery trips.

### 1.2. Product Position Statement

### 1.3. Value Proposition and Customer Segment
MyGroceryAssistant is a grocery tracking app that helps young adults who often forget to pick up certain grocery items remember when and what to buy from the store by providing an interactive calendar and reminder feature that offers easier use than other competitors. 

## 2. Stakeholders
Developers - Develop and maintain the software. Developers will also test and make changes to problems found to improve clients experience.

Users/Interviewees - The users will test the product through normal use and this will reveal problems and concerns with the software that we can improve for future users.

Competitors - Other shopping/budgeting apps that have similar features to ours. We can compare our app to the competition to get a gauge on our ideas and how they might perform. 

## 3. Functional Requirements (Features)

1. Automatically track the common items bought by the user and create a portfolio of their groceries.
2. Compare the price of each item to other stores in order to find the best overall priced shopping list and which store to get it.
3. Generate a calendar for the user that shows when they will need to restock on their common items and where to go. 
4. Remind the user using various methods of notifications for when they need to go to the store based off of their personalized portfolio and calendar.
5. Track seasonal items such as produce, holiday items, specials, etc and recommend items based on the season to the user. 
6. Allow the user to enter which items they bought, where they bought them, and what price they bought them for in order to better optimize their portfolio.
7. Allow the user to interact easily with the calendar, portfolio, settings, etc using a minimalist design with high functionality and customization. 
8. Allow any errors recieved by the app to be immediately sent as a report to the developers with an estimated risk level attached based on number of users impacted. 

## 4. Non-Functional Requirements

1. Portability: This is very important because the app should be available on a mobile device with full functionality in order to use the application while shopping. 
2. Flexibility: The app should be able to help with a large variety of situations and shopping experiences. Because of this, the app will be very flexible in order to handle any shopping experience that the user may encounter. 
3. Reliability: The app needs to be very consistent so that every time the user goes shopping, it will perform accurately every time to ensure the user gets all of the products they need. 
4. Performance: Because there is not many moving parts happening at once, the performance shouldn't be an issue. It will need to connect to the MyGroceryAssistant servers quickly and generate a solid portfolio, calendar, and price mapping. Other than the connection side of the application, the UI will be minimalistic, allowing for a fast user experience. 
5. Security: The security of any app is important, however there wont be much personal information stored in the app besides your location, name, and grocery items. Because of this, there will be very little danger in using this app. Each user will create an account using their email and a password, allowing for extra protection for each user.  

## 5. MVP
Many young adults tend to forget little items when going to the grocery store. MyGroceryAssistant can help relieve some of these small yet annoying issues. The main features of the app include a calendar that keeps track of what items you should buy and on what day. This feature will then add all grocery items into a list once the certain date is reached, keeping track of all the items that you may want to go out and re-buy. The second main feature of the app is the reminder function. This part of the app will give you weekly reminders of what items you may need for the upcoming week. We can test these features by providing the app different groups of grocery shoppers making sure the app responds with a unique and beneficial response.

## 6. Use Cases

### 6.1. Use Case Diagram

### 6.2. Use Case Descriptions and Interface Sketch

**Use-Case: Submit online grocery list**

1 Brief Description

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gives store your grocery list as an online order that is ready for curb side pickup.

2 Actor

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Customer

3 Preconditions

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The user has a grocery list already

4 Main Flow

1.	The user access custom grocery list.
2.	User can finialize their list if any changes are needed.
3.	User submits list and waits until order is ready.
4.	The use case ends.
	
5 Alternative Flows

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If in step 3 of the basic flow a specfic item is out of stock, then 

1.	User will be notified and given other possible stores if they have said item
2.	The use case resumes at step 3

6 Post-conditions
	
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Their grocery list would be picked and ready for curbside pickup.

**Use case: Recommend items**

Actor: Admin

Description: The admin recommends a list of items that all shoppers on the app can see

Pre-Conditions: The admin has a confirmed list that has been ‘ok’d’ by the group of owners

Post-Conditions: The admin has posted a list and all users can now see the list

Main Flow: The admin creates a list of potential items a group of users might like and pushes the list out onto the app. Users can then see this list on their browse page 

Alternative Flow: Admins can send out reminders to all users with recommended/ seasonal / holiday items. 
  
## 7. User Stories

* As a college student I want this app to remind me what items to buy so I don’t have to make multiple trips to the store (Priority #, 10 hours)
* As a young adult I want this app to keep track of when I buy groceries so I can budget easier (Priority #, 6 hours)
* As a developer I want to make a price match feature to give the user the best possible price on an item.(Priority, approximately 10 hours)
* As a user I want to be able to update grocery list so I can constantly optimize my list to suit my needs(Priority #1, approximately 2 hours)
  
## 8. Issue Tracker
