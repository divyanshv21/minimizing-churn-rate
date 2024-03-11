# Minimizing churn rate of subscription products through analysis of financial habits

Subscription Products often are the main source of revenue for companies across all industries. These products can come in the form of a 'one size fits all' overcompassing subscription or in multi-level memberships. Regardless of how they structure their memberships or what industry they are in, companies almost always try to minimize customer churn (a.k.a. subscription cancellations). To retain their customers, these companies first need to identify behavioural patterns that act as catalysts in disengagement with the product.

- **Market:** The target audience is the entirety of a company's subscription base. They are the ones companies want to keep.

- **Product:** The subscription products that customers are already enrolled in can provide value that users may not have imagined or that they may have forgotten.

- **Goal:** The objective of this model is to predict which users are likely to churn so that the company can focus on re-engaging these users with the product. These efforts can be email reminders about the benefits of the product, especially focusing on features that are new or that the user has shown to value.

I will be identifying users who are likely to cancel their subscriptions so that we can start building new features that they may be interested in. These features can increase the engagement and interest of our users towards the product.

**Data:** By subscribing to the membership, our customers have provided us with data on their finances, as well as how they handle those finances through the product. We also have some demographic information we acquired from them during the sign-up process.

## Conclusion

- Our model has provided us with an indication of which users are likely to churn. We have purposefully left the date of the expected churn open-ended because we are focused on only the features that indicate disengagement with the product and not the exact manner (like timeframe) in which users will disengage. In this case study we have chosen this open-ended emphasis to get a sense of those who are even just a bit likely to churn because we are not aiming to create new products for people who are going to leave us for sure, but for people who are starting to lose interest in the app.
  
- If, after creating new product features, we start seeing our model predict that fewer of our users are going to churn, then we can assume our customers are feeling more engaged with what we are offering them. We can move forward with these efforts by inquiring about the opinions of our users about our new features (eg. polls). If we want to transition into predicting churn more accurately, in order to
put emphasis strictly on those leaving us, and then we can add a time dimension to churn, which would add more accuracy to our model.
