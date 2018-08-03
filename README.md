# Search Results Analysis

Author: Bingyi Li

## Goal

Build a model to accurately predict the relevance of search results.

## Brief Intro
So many of our favorite daily activities are mediated by proprietary search algorithms. Whether you're trying to find a stream of that reality TV show on cat herding or shopping an eCommerce site for a new set of Japanese sushi knives, the relevance of search results is often responsible for your happiness. Currently, small online businesses have no good way of evaluating the performance of their search algorithms, making it difficult for them to provide an exceptional customer experience.

The goal of this project is to create a model that can be used to measure the relevance of search results. In doing so, small business owners will be able to match the experience provided by more resource rich competitors. It will also provide more established businesses a model to test against. Given the queries and resulting product descriptions from leading eCommerce sites, this project is to evaluate the accuracy of their search algorithms.

## Description of Data

train.csv - the training data set includes:</br>
  - id: Product id
  - query: Search term used
  - product_description: The full product description along with HTML formatting tags
  - median_relevance: Median relevance score by 3 raters. This value is an integer between 1 and 4
  - relevance_variance: Variance of the relevance scores given by raters
  
test.csv - the test data set includes:<br/>
  - id: Product id
  - query: Search term used
  - product_description: The full product description along with HTML formatting tags
  
## Deliverable

The presentation slide is a high-level demonstration of the discussion.
