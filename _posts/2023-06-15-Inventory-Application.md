---
layout: post
title: Inventory Application
subtitle: Showcase for inventory application
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: 
comments: true
---

This section will cover the Inventory Application.

The application I chose to enhance for the Software Design/Engineering was an Inventory App from CS 360. For this course, we had to create an Android mobile application that had the ability to create, read, update, and delete from a database within the app. It also required a user sign in and self-user registration. The original application accomplished all of these, but it was very barebone and fulfilled the minimum.
First, I wanted to add an actual list to the application that will dynamically show the items in the inventory. Originally, the application would only show the items via a pop up. This is possible using a ListView and the application now looks better showing the inventory items. The “Add items” screen now displays on a separate screen and the “edit” and “delete” items are directly in the list. The “register user” screen has not changed in function. There is now a sign out button on the app bar within the inventory screen.
The main idea behind these enhancements was to improve the user experience. In the original app, something that stood out to me while reviewing it was the lack of intuitiveness across the app. The adding/updating/deleting of items was not very user friendly, as was registering a user account. It was also missing basic items and functions, like a “back” button or “sign out” button, and some functions like returning to the previous screen automatically once the main action on the current screen has been done, like registering a user or adding an item for example. Making sure that the layout is simple, and button designs make sense for what they do (like a plus sign for “adding” or “increasing” or an “X” or trash icon for “deleting/removing” for example) was important for me. If a real user were to use my application, having too much clutter would be distracting and button designs that don’t make sense for what they do would cause frustration.
Within the code, there have been improvements to make the application easier to understand for other developers. There are now models for items and users, and they are stored in the databases. Originally, the DB functions passed in strings directly into the columns, which generally may not be good practice. Making these objects and storing the objects instead allows for cleaner and easier management. The models are defined with a familiar and consistent structure (constructors, getters, setters, etc.) and the DB functions all have consistent data manipulation methods. They also now have meaningful method names (like “getItem()” or “getUser()” rather than “getData()” for example) This ensures that other developers will understand what these methods are doing and it is less confusing to work with. Unnecessary code lines have been cleaned up and unused methods, variables, objects, imports, etc. have been cleaned up.
With these enhancements, I have been able to improve on the basic functions of the application without compromising any of those existing functions. There have also been some improvements to the look and navigation of the application. I was able to solve the problem of not being able to edit an item name in the list and now these can be edited, along with the quantity. I was also able to maintain a simple look of the application and implement meaningful navigational buttons and icons. This demonstrates that I am able to create an application that accounts for end user experience, since a clean and simple layout and easy navigation is very important for a mobile application.
Below are screenshots of screens from the original build and the enhanced build. The original is on the left and enhanced on the right.

![MainActivity](https://github.com/Fxvargas/Fxvargas.github.io/assets/61395074/66de5abb-47fb-442c-b41b-0f60614abb39)![MainScreen](https://github.com/Fxvargas/Fxvargas.github.io/assets/61395074/e72c04cb-0f88-4cbd-b8b2-971e5a77fcad)

![RegisterActivity](https://github.com/Fxvargas/Fxvargas.github.io/assets/61395074/53275364-ed19-4816-b441-15220ebda1cf)![RegisterActivity](https://github.com/Fxvargas/Fxvargas.github.io/assets/61395074/086752b9-0661-4df0-9925-f6a37dc573ba)


![MainScreen](https://github.com/Fxvargas/Fxvargas.github.io/assets/61395074/adb97f04-8d32-416f-8cfa-880b16f21f9e)![MainActivity](https://github.com/Fxvargas/Fxvargas.github.io/assets/61395074/591498bd-b4c0-41b7-aa12-031ecc682b20)


![MainScreen_Items](https://github.com/Fxvargas/Fxvargas.github.io/assets/61395074/ddf56482-ee51-4534-a0f1-aaa8cc1ad83b)![MainActivity_Edit](https://github.com/Fxvargas/Fxvargas.github.io/assets/61395074/dcf1697f-d326-4649-ac02-154d2206a659)

The following screen is only available in the enhanced app:

![AddActivity](https://github.com/Fxvargas/Fxvargas.github.io/assets/61395074/517039dd-95fe-4468-b6f0-f588c4f39aa7)
