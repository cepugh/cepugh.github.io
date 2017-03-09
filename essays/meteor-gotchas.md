---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-03-09
labels:
  - Software Engineering
  - Meteor
---
### Meteor

As a brand new developer of web applications, any framework is a bit intimidating! Meteor in particular has some mixed reviews and opinions, mostly from developers who have some experience with other frameworks and the LAMP stack who feel that the methodology of Meteor is bit crazy. Luckily I have no experience whatsoever, so it all seems a bit crazy. I was initially intimidated, then a bit relieved as the different tutorials started to make sense. First, we did tutorials that started from the ground and worked there way up. We were creating all the files and coding the application line by line. This works great for me, I can look up every piece of code I don't understand as we go. Then, the professor introduced us to a few WODs that were based off of a template. At that point I felt like I wanted to throw the towel in! However, after a few hours of tediously going through the code, I felt a bit better and now I am on my way to creating some apps (basic apps of course)!

#### My big problem
The digits assignment to create an app based off of a template that recorded contact information utilizing a few basic foundations for Meteor app creation threw me through a few loops. Without the example videos from the professor, I never would have made it through. My biggest problem was that there was a lot of code that I didn't quite understand what was happening underneath. For instance, the edit contact page was almost identical to the add contact page, however it needed to call back to the Mongo collection to auto fill in the fields from the specific document we were trying to edit. For the life of me, I couldn’t get the fields to fill back in. My problem was that there was a helper function called "contactDataField" that used the FlowRouter.getParam to grab the id of the particular contact I was editing and use that value to go back into the Mongo collection and grab all those values to repopulate the form. I had to go back and learn how FlowRouter worked for me to trouble shoot where my typo was and great everything working smoothly. It is super important to understand how things work under the hood or small typos can remain hidden and destroy an application! 


#### The Best Way Forward
I have managed to make my way and complete the digits assignment and am now attempting the extra credit assignment to build onto the application. The first task is to do some field validation for the phone numbers and only allow digits instead of string and in the (XXX-XXX-XXXX) format. Initially, I went straight to Google to try and read about schema validation, however I feel like I have to read the entire documentation to figure out how this works. In addition, there seems to not be a lot of crowd sourcing questions on the Internet for Meteor. Maybe because it is a newer framework. Either way, I would be happy to get any advice on how people take a brand new task and find information quickly on solving it!


