---
layout: essay
type: essay
title: "Why Should We Consider Design Patterns"
# All dates must be YYYY-MM-DD format!
date: 2025-04-24
published: false
labels:
  - Coding
  - Database
---

<img width="200px" class="rounded float-start pe-4" src="../img/design_patterns.jpg">

## Design Patterns

Design patterns are a software engineering concept describing a general approach to solving a certain kind of problem. It applies to problems irrespective of the coding language in which applications are being programmed in. These concepts can be reused and applied to specific problems with some tweaks to suit the situation. Many design patterns may have been natively implemented into programs and coding languages such as singletons(static classes) and iterators in C# and Java. Design patterns also come with disadvantages/complications compared with standard methods of implementation, this is important to consider when using a design pattern in software engineering.

## Are they actually useful?

Since there are many examples of design pattern implementations in languages, libraries, and game engines, surely that must been many of them are quite useful. While this may be the case, it is always important to distinguish whether a design pattern is actually helpful and when they aren't, these are known as antipatterns. An example of this is when I was making a class to handle playing music in a game. My initial approach was to make a single object that would handle playing and stopping music, switching tracks, and anything else that would be required. However, it was hard to implement certain kinds of functionality like when in the level should music be switched, and how can we fade in and fade out music if it is all coming from one object. This is an example of a God Object antipattern, where one class is burdoned with too much functionality and it makes it difficult to change or test features. Therefore, it is good practice to find an appropriate and suitable design pattern based on what you want your program to accomplish as well as any foreseeable enhancements. One design pattern that I have utilized is the Observer design pattern, where an observer is notified of a change in a subject and the observer reacts to that change. In this application, I needed to add user reported sightings of birds to multiple pages of a website. The website pages were observers updating variables like number of sightings, sightings on a user's profile, and updating locations of birds based on sightings. This is an example of multiple observers and a single subject and this design pattern was seamless to implement due to the way database relationships are structured.

## Conclusions

Design patterns are important to learn because it allows you to write forward thinking code. You can apply the same concepts to multiple problems and understand the advantages and disadvantages of your approach. While implementations depend on coding language, what libraries you use, database structure and relationships, among other things, design patterns have served to be applicable to many problems and beneficial to learn about.
