# AI-BASED-RECOMMECDATION-SYSTEM

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
