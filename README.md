# Market Basket Analysis

### Purpose of Market Basket Analysis 
Finding items that buyers desire to buy is the major goal of market basket analysis. 
Market basket analysis may help sales and marketing teams develop more effective product placement, pricing, cross-sell, and up-sell tactics


### We will be utilizing two algorithm for Market Basket Analysis 

+ Apriori Algorithm 
+ FP growth

### Understanding Association Rules is critical in understanding product relationship during purchase. 

<img width="634" alt="Screenshot 2023-02-19 at 10 20 05 PM" src="https://user-images.githubusercontent.com/80999165/220002982-4dfa373a-9334-4588-b47a-458d4d80f070.png">


What we see above is how often Milk(*Consequent*) was bought when Bread & Egg (*Antecedent*) were bought together


#### There are 3 metrics to help us understand the relationship between the two 

+ Support
+ Confidence
+ Lift

#### Support 

Support as an measure gives an idea of how frequent an itemset is in all the transactions.  For example, one might want to consider only the itemsets which occur at least 50 times out of a total of 10,000 transactions i.e. support = 0.005. 
If an itemset happens to have a very low support, we do not have enough information on the relationship between its items and hence no conclusions can be drawn from such a rule.

#### Confidence

This measure defines the likeliness of occurrence of consequent on the cart given that the cart already has the antecedents. That is to answer the question — of all the transactions containing say, {Captain Crunch}, how many also had {Milk} on them? We can say by common knowledge that {Captain Crunch} → {Milk} should be a high confidence rule. Technically, confidence is the conditional probability of occurrence of consequent given the antecedent.

#### Lift 

Lift is an important measure. A value of lift greater than 1 vouches for high association between {Y} and {X}. 
More the value of lift, greater are the chances of preference to buy {Y} if the customer has already bought {X}. 
Lift is the measure that will help store managers to decide product placements on aisle.

### Screegrab from our Analysis 


<img width="1079" alt="Screenshot 2023-02-19 at 10 46 45 PM" src="https://user-images.githubusercontent.com/80999165/220005145-3593a7c9-83de-4feb-9f3c-6ca6d0870033.png">



