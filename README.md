Quora is a place to gain and share knowledge—about anything. It’s a platform to ask questions and connect with people who contribute unique insights and quality answers. This empowers people to learn from each other and to better understand the world.

Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.

# Quora-Question-Pair-Similarity
Identify which questions asked on Quora are duplicates of questions that have already been asked.This could be useful to instantly provide answers to questions that have already been answered,predict whether a pair of questions are duplicates or not.

## Real world/Business Objectives and Constraints 

  1. The cost of a mis-classification can be very high.
  2. You would want a probability of a pair of questions to be duplicates so that you can choose any threshold of choice.
  3. No strict latency concerns.
  4. Interpretability is partially important.
    
<h3> 2.2.1 Type of Machine Leaning Problem </h3>

<p> It is a binary classification problem, for a given pair of questions we need to predict if they are duplicate or not. </p>

<h3> 2.2.2 Performance Metric </h3>

Source: https://www.kaggle.com/c/quora-question-pairs#evaluation

Metric(s): 
* log-loss : https://www.kaggle.com/wiki/LogarithmicLoss
* Binary Confusion Matrix
