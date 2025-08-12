# AI-BASED-RECOMMECDATION-SYSTEM

COMPANY: CODTECH IT SOLUTIONS

NAME : A.BRITTO RAJ

INTERN ID : CT04DZ331

DOMAIN : JAVA

DURATION : 4 WEEKS

MENTOR : NEELA SANTHOSH KUMAR


# Java Product Recommendation System using Apache Mahout

## Overview
This is a simple Java console application that recommends products to users based on their past preferences.  
It demonstrates the use of *Apache Mahout* for collaborative filtering, along with *Java I/O* for reading rating data from a CSV file.

The project is aimed at beginners who want to learn how to build recommendation systems in Java using Mahout and explore how user-based collaborative filtering works.

## Features
- Generates product/content recommendations for a given user
- Uses *user-based collaborative filtering* for predictions
- Reads ratings data from an external CSV file
- Predicts ratings for items the user hasn’t interacted with
- Simple console-based output

## Technologies Used
- Java (Core Java)
- Apache Mahout (mahout-core)
- CSV file for storing user-item ratings
- Pearson Correlation Similarity for measuring user similarity

## How It Works
1. *Prepare Ratings Data* – Ratings are stored in a CSV file in the format:  
   userID,itemID,rating
2. *Load Data* – The application reads the CSV file using Mahout’s FileDataModel.
3. *Similarity Calculation* – Mahout calculates user similarity using Pearson Correlation.
4. *Recommendation Generation* – The system recommends top N items for a target user.
5. *Display Output* – Recommended items with predicted preference values are printed on the console.

## Running the Project in IntelliJ IDEA
1. Create a new Java project in IntelliJ IDEA.
2. Add *Apache Mahout* dependency in your pom.xml (for Maven) or add the required JARs manually.
3. Place your ratings.csv file inside a data folder in the project directory.
4. Create a Java file (e.g., RecommenderApp.java) and copy the provided code into it.
5. *Run the Application:*
   - Right-click RecommenderApp.java → *Run 'RecommenderApp.main()'*
6. The console will display recommended products for the specified user.

## Output
