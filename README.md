# Starbucks Capstone Project
## Recommending offers for Starbucks customers
### Installation
- numpy
- pandas
- matplotlib
- sklearn
- json
- math


### Project Motivation
We were given some simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks. The goal was to dive into the data, explore the data and make some visualizations.
The final question we try to answer in this project is:
### Can we predict, whether the customer should receive an offer of type (bogo, discount, informational)?


### File Description
**portfolio.json**
* id (string) - offer id
* offer_type (string) - type of offer ie BOGO, discount, informational
* difficulty (int) - minimum required spend to complete an offer
* reward (int) - reward given for completing an offer
* duration (int) - time for offer to be open, in days
* channels (list of strings)

**profile.json**
* age (int) - age of the customer 
* became_member_on (int) - date when customer created an app account
* gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
* id (str) - customer id
* income (float) - customer's income

**transcript.json**
* event (str) - record description (ie transaction, offer received, offer viewed, etc.)
* person (str) - customer id
* time (int) - time in hours since start of test. The data begins at time t=0
* value - (dict of strings) - either an offer id or transaction amount depending on the record

### Result Summary
The main findings can be found in the code and are discussed in the post here:  https://medium.com/@thomas.grassinger/recommending-offers-for-starbucks-customers-bd7bdc36ea25

### Acknowledges
First, I want to thank the udacity team for this great course and all the material and challenges. Of course also the mentors for being so supportive. And a big thanks to starbucks for providing the data and giving the opportunity to work with real world problems.


can be found here: https://medium.com/@thomas.grassinger/recommending-offers-for-starbucks-customers-bd7bdc36ea25
