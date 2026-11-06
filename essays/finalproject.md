
---
layout: essay
type: essay
title: "Final Project Idea"
# All dates must be YYYY-MM-DD format!
date: 2026-11-06
published: true
labels:
  - Software Engineering
  - Nextjs
  - Food and Nutrition
  - Campus Community
  - ICS 314
---

<style>
.container.py-4 > h1,
.container.py-4 h2 {
  color: #0f766e;
}

.container.py-4 h2 {
  border-bottom: 2px solid #99d5cb;
  padding-bottom: 8px;
  margin-top: 28px;
}

.container.py-4 a {
  color: #0f766e;
}

.container.py-4 > hr {
  border-color: #99d5cb;
  opacity: 1;
}
</style>

## Project: Food Fitness Feed

**Proposers:**

- Herman
- Aaron
- Miguel

**Project Ideas Considered:**

1. Food Fitness Feed
2. Bathroom Raider
3. AI Advisor

## Overview

**The Problem:** Most college students are unfamiliar with the area surrounding their campus, especially when moving to a new location. Not everyone has reliable access to transportation whenever they want to purchase food that aligns with their nutritional goals, dietary restrictions, or budget. Students may also be unaware of nearby restaurants, grocery stores, and campus dining options that meet their needs.

Finding affordable and nutritious meals can require students to research multiple websites, compare menu prices, check nutritional information, and determine whether a location is accessible by walking, public transportation, or driving. This process can be time-consuming, especially for students balancing academics, work, and other responsibilities.

**The Solution:** Food Fitness Feed is a web application designed to help students discover affordable and nutritious food options throughout Oahu. Users will be able to enter their budget, nutritional goals, dietary preferences, restrictions, and available transportation methods to receive recommendations for restaurants, grocery stores, and campus dining options that meet their needs.

The website will allow students to compare meal prices, nutritional information, ratings, and travel distances without having to research unfamiliar locations independently.

Additionally, Food Fitness Feed will feature a community dashboard where students can share their experiences, recommend meals, and review local food vendors. This will allow users with similar preferences to learn from one another before deciding where to eat.

The main goal of Food Fitness Feed is to make finding affordable, accessible, and nutritious food easier for college students.

## Approach

The website will be developed using Next.js, React, Bootstrap 5, Prisma with PostgreSQL, and GitHub. Food Fitness Feed will function as an interactive, island-wide food discovery platform where users can search for food alternatives based on their personal preferences and nutritional goals.

Users will be able to enter different search criteria, including their budget, dietary preferences, ingredients, desired food types, and transportation availability. The application will display relevant food recommendations based on these inputs.

Each food recommendation will contain useful information such as the meal name, restaurant or vendor, estimated cost, calorie information when available, user ratings, and location.

Visitors who are not logged in will have access to basic search functionality, allowing them to browse available food vendors and filter results based on their budget or preferences.

Users who register with their hawaii.edu account or another email address will gain access to additional features. Registered users will be able to create a profile containing their dietary preferences, nutritional goals, and favorite food options.

Registered users will also be able to view detailed ingredient information when available, read reviews from other students, submit ratings and feedback, and create their own food recommendations for the community.

The website will include a community dashboard where students can share meals they have tried and provide useful information for other users. Users can also save their favorite recommendations for future reference.

To maintain the quality and reliability of the platform, administrators will have access to moderation features. Administrators can flag inappropriate posts, remove misleading content, manage user accounts, and monitor submitted information to protect user privacy.

The website will use a recommendation system that considers factors such as price, dietary preferences, nutritional information, and travel distance to display food options that are most relevant to each user's needs.

## Roles

- **Visitors:** Browse food recommendations, search for nearby vendors, filter food options by budget and preferences, and view basic meal information without creating an account.

- **Registered Users:** Have all visitor privileges and can create profiles, save dietary preferences, set nutritional goals, view detailed meal information, post recommendations, write reviews, submit ratings, and save favorite meals or vendors.

- **Admins:** Have all registered user privileges and can manage food listings, moderate community posts, remove inappropriate reviews, manage user accounts, and maintain accurate information throughout the platform.

## Mockup Page Ideas

- **Landing Page:** Introduces Food Fitness Feed, explains the purpose of the website, and provides a search bar where users can begin searching for food based on their preferences.

- **Food Discovery Page:** Displays a searchable and filterable list of food vendors and meal recommendations. Users can filter results based on budget, dietary restrictions, food type, and location.

- **Food Detail Page:** Shows detailed information about a selected meal, including its price, available nutritional information, ingredients, vendor location, ratings, and reviews.

- **Community Dashboard Page:** Allows registered users to browse food recommendations and reviews submitted by other students. Users can share their experiences and discover meals recommended by the community.

- **Create Recommendation Page:** Allows registered users to submit their own food recommendations by providing the meal name, vendor, price, nutritional details, description, and personal rating.

- **User Home Page:** Displays the user's dietary preferences, nutritional goals, saved meals, favorite vendors, and previous reviews or recommendations.

- **Map Page:** Displays nearby restaurants, grocery stores, and campus dining locations on an interactive map to help users find accessible food options.

- **Admin Home Page:** Provides administrators with tools to manage food listings, review user submissions, remove inappropriate content, and manage registered accounts.

## Use Case Ideas

- A visitor goes to the landing page and searches for food vendors that offer meals within their specified budget without needing to log in.

- A visitor searches for restaurants near the UH Manoa campus and filters results based on walking distance and affordability.

- A new user visits the landing page, registers for an account, and sets up a profile with dietary preferences, nutritional goals, and transportation options.

- A registered user searches for meals based on dietary restrictions and receives recommendations from restaurants and grocery stores that meet their preferences.

- A registered user selects a food recommendation to view its price, available nutritional information, ingredients, location, and reviews from other students.

- A registered user visits a restaurant, returns to the website, and submits a rating and review to share their experience with the community.

- A registered user creates a new post recommending an affordable meal they discovered near campus, including the meal's price, location, and description.

- A registered user saves a food recommendation to their favorites and accesses it later through their personal dashboard.

- An administrator logs in, reviews a reported community post, and removes inappropriate or misleading information from the platform.

## Beyond the Basics

After implementing the basic functionality, here are ideas for more advanced features:

- **Interactive Vendor Map:** Display restaurants, grocery stores, and campus dining options on an interactive map so users can find nearby food vendors based on their location and transportation options.

- **Meal Price Comparisons:** Allow students to compare the costs of similar meals from different vendors to identify affordable options.

- **Vendor Operating Hours:** Display restaurant and grocery store operating hours so students can determine when food options are available.

- **Community Reviews and Ratings:** Allow registered users to write reviews and rate food vendors. These ratings can help other students decide which food options best fit their preferences.

- **Nutritional Information:** Provide available calorie information, macronutrients, ingredients, and other nutritional details to help users make informed food choices.

- **Personalized Food Recommendations:** Develop a recommendation system that ranks meals based on a user's budget, dietary preferences, nutritional goals, and available transportation.

- **AI Food Assistant:** Integrate an AI assistant that helps users discover meals based on conversational requests, such as "Find an affordable vegetarian lunch within walking distance of UH Manoa." The assistant would use the application's verified food listings to generate recommendations.

- **Favorite Meals and Vendors:** Allow registered users to save their favorite meals and restaurants for easier access.

- **Community Recommendation Feed:** Introduce a feed where students can browse popular recommendations, discover highly rated meals, and see food options shared by other users.

- **Transportation-Based Recommendations:** Use estimated walking, driving, or public transportation distances to prioritize food vendors that students can reasonably access.
