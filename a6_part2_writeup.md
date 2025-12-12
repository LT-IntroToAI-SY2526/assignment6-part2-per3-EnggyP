# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.

**YOUR ANSWER:**
1. Most Important: Squarefeet
2. Bedrooms
3. Bathrooms
4. Least Important: Age

**Explanation:**
I determined this ranking since the Squarefeet vs Price shows the strongest upward trend and the points are closer to the line, making it more linear. Bedrooms vs Price has a positive upward trend as well, but it is more clustered and less linear. Bathrooms vs Price has a graph of the price overlapping and the relationship is also clustered together. Age vs Price grapgh is more scattered throughout, there is no linear nor consistency of whether it is increasing or decreasing. 



---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"

**Feature 1:**
For every additional square foot a house has, the price increases by about $156.

**Feature 2:**
Adding one more bathroom increases the price by about $112,700 on average.

---

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:**
My model's R² score is 0.9. This tells me that my model predictions are almost identical to the actual house prices in my dataset. There is room for improvement, such as adding more details about the house location and its appliances, since it could still impact the price value for houses when a person is trying to purchase one and figure out how much they have to pay monthly. 


---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:**
Electricity prices

**Why it would help:**
It would help improve my house price predictions since utility costs affect the affordability of a home. Buyers often consider long-term living expenses. 

**Feature 2:**
Location 

**Why it would help:**
It would also help improve my house price predictions since it is the most critical for drivers. Depending on the distance from the house to schools, workplaces, shopping centers, public transport, and neighborhood safety all influence demand and the price

---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

**YOUR ANSWER:**
I would not trust this model to predict the price of a house like that because The model has not seen examples with large values for bedrooms, bathrooms, or square footage. Leading to unreliable predictions. In addition, larger homes may have different pricing structures, such as luxury finishes that aren’t added in the model. 

