
# Covid-Assistance-Bot

## Overview

The Covid-Assistance-Bot is a project aimed at providing assistance and resources to individuals in need during the Covid-19 pandemic. Leveraging Twitter data, AWS services, and a custom-built bot, this project offers real-time support by identifying tweets related to Covid-19 assistance and responding with relevant information.

## Functionality

**1. Tweet Scraping**

The bot continuously monitors Twitter for tweets containing keywords related to Covid-19 assistance, such as "covid help", "need oxygen", "vaccine assistance", etc.
Using Twitter APIs or web scraping techniques, relevant tweets are extracted for further processing.

**3. Data Processing in AWS**

The extracted tweets are processed in the AWS environment using various services:

-AWS Lambda: Serverless functions are used for data processing tasks, such as filtering tweets, extracting relevant information, and triggering responses.

-Amazon S3: Storage service utilized for storing extracted tweet data and other necessary resources.

-Amazon DynamoDB: NoSQL database for storing processed tweet data, user information, and other relevant details.

**3. Bot Development**

A custom bot is developed to interact with Twitter users based on the processed data.

The bot is capable of:

-Analyzing tweet content to understand user needs.

-Generating appropriate responses with useful information or resources.

-Interacting with Twitter users by mentioning their handles in replies.

-Handling multiple concurrent requests efficiently.
