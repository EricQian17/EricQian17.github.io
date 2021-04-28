---
title:  "Food Calorie Log"
header:
  teaser: "/assets/images/500x300.png"
categories: 
  - Posts
tags:
  - projects
---

This was a project done in my free time that allowed a user to search and log their food/calorie intake for each day. 
Project was coded using Java and UI was built using Scenebuilder FXML. The data was pulled from FDC's Food database of branded names uploaded onto Mongodb Atlas so users can 
search up the foods they ate without having to enter their own. Due to limit on the free cluster the nutrients data could not fit into the database and to bypass this I added new
fields where users can input their data for calories, fat, protein, and carbs. Users are also able to enter new foods that do not show up in databases or delete entries from the database.

# UI Design   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  UI w/ User input and Modification

<img src="https://user-images.githubusercontent.com/42530687/116464104-8f8e4500-a839-11eb-97c2-3ce696b624bf.png" alt="drawing" width="500"/>&nbsp;&nbsp;<img src="https://user-images.githubusercontent.com/42530687/116464382-eac03780-a839-11eb-8f22-d8a496cb6be7.png" alt="drawing" width="500"/>


Then after submitting the entry you can view the logs by clicking the "Check Logs" button and it will allow you to choose to display all dates if left empty or a specific date to display
all entries on that date. If there was a mistake users can delete the entry by selecting the entry and pressing the delete button on the UI.

# User Logs UI&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Date Filter Example

<img src="https://user-images.githubusercontent.com/42530687/116465610-74bcd000-a83b-11eb-8b71-751c24ae3ac4.png" alt="drawing" width="500"/>&nbsp;&nbsp;<img src="https://user-images.githubusercontent.com/42530687/116465772-ab92e600-a83b-11eb-959d-eabeaefc3341.png" alt="drawing" width="500"/>


&nbsp;

&nbsp;

Check it out [here][food-log-code].

[food-log-code]: https://github.com/EricQian17/Food_Calorie_Tracker

