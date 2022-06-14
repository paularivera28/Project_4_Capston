# Project_4_Capston

### Table of Contents

1. [Libraries](#Libraries)
2. [Project Motivation](#motivation)
3. [File Description](#Description)
4. [Instructions](#Instructions)
5. [Results](#Results)

## Installation <a name="installation"></a>

In this project I use the following libraries in python:

* Pandas
* Numpy
* math
* json
* matplotlib
* sklearn

## Project Motivation <a name="motivation"></a>

This project is part of the Data Scientist Nanodegree Program of udacity, who has the aim to put in action all the sill we learn in the program, the idea is to understand the behavior of the clients based on thei characteristics and the interactions with the type of offert they recived in the final transaction or purshase by different media like web, social or mobile with the objective of determine the features that make and ofert succesful.

## File Descriptions <a name="files"></a>

The repositori has the following 3 folders

- **portfolio.json**

- id (string) - offer id
- offer_type (string) - type of offer ie BOGO, discount, informational
- difficulty (int) - minimum required spend to complete an offer
- reward (int) - reward given for completing an offer
- duration (int) - time for offer to be open, in days
- channels (list of strings)

- **profile.json**

- age (int) - age of the customer
- became_member_on (int) - date when customer created an app account
- gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
- id (str) - customer id
- income (float) - customer's income

- **transcript.json**

- event (str) - record description (ie transaction, offer received, offer viewed, etc.)
- person (str) - customer id
- time (int) - time in hours since start of test. The data begins at time t=0
- value - (dict of strings) - either an offer id or transaction amount depending on the record

## Results<a name="results"></a>

The blog with the result of the analisis is in this link  [post](https://paularivera288.wixsite.com/website/post/exploring-the-seattle-airbnb-data)



