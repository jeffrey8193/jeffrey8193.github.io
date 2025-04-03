---
layout: essay
type: essay
title: "Final Project Idea"
date: 2025-04-01
published: true
labels:
  - Software Engineering
  - Nextjs
---

## Authors
Alana Wesly, Ace Reyes, Chayanika Devi, Jeffrey Jian

## Overview

_The problem:_ The Manoa campus is home to a diverse collection of plant and animal species, including many native to Hawaii. As a result, there are many avid bird watchers and people interested in where to find bird species, what time of day can you see these birds, and what bird species are you actually looking at. How can you find the bird you are looking for on campus reliably?

_The solution:_ Design a website to collect a list of birds and various information about them such as spotted locations, species and name, and what time of day and what part of the year can you spot them. Users can login and post information about where the birds have been spotted to better aid other bird watchers in finding them. Include features that will help frequent goers of UH Manoa, mainly students, such as filtering birds based on their schedule. The goal is to make bird watching in Manoa easier and also accomodate students.

## Approach

Users can create an account and update information about a bird species. Each bird species will have profile listing information about their name/species, location on campus, description, and the time of day and time of year they can be spotted on campus. Users can add information in the form of bird sightings, including location and date of the sighting. In addition there will be features geared toward accomodating a student's schedule, a student can add their schedule information and the site will filter based on their available time slots and location of classes which birds they can see.

## Mockup page ideas

Our current idea is for this project to make use of 4 distinct pages: a main landing page displaying cards containing the information of different observed bird species, a login page where users can register and sign in, a “report sighting” page where users can add the birds that they have seen and the information they have of them (image, description, location etc…) to a database, and a “list sightings” page where users can see all of the birds they have seen previously, as well as add, delete, or edit past bird sightings.

Or, more simply:
- Landing page with all the birds
- User login page
- Report sighting page
- List sightings page
- Add schedule and filter based on schedule
  
## Use case ideas

There are many possible use cases for this website. An initial one is, a new user going to the landing page, which is the home page, and making a new user account. Another use case is a returning user going to the landing page, which goes to the home page, signing in with their account, and navigating to the report sighting page to add information about a bird they have seen. Additionally, any user, with or without signing in, can browse the list of birds on the landing page, and a signed in user can navigate to the list sightings page and view and edit their past sightings. 

## Beyond the basics

- Create a map that can be filtered by bird species. The map should show the bird species name, origin of the species whether it is migratory or Hawaiian bird once you click on the spotted location. 
- Add bird calls to each species
- A tracker displaying a user’s streak of how many days in a row they have reported a bird sighting, and a graph showing their rate of birds sighted over time.
