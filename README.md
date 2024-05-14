# Targeted Marketing for Airbnb Property Hosts
We leverage advanced analytics techniques to pinpoint properties registered with Airbnb that might potentially leave the platform in the upcoming quarter. This strategic approach enables the organization to identify specific properties, allowing for the creation of targeted retention marketing strategies. This ensures optimized resource allocation by avoiding broad, indiscriminate spending on all properties.

![image](https://github.com/devallasaitej/Airbnb_Targeted_Marketing/assets/64268620/12fbb73e-3836-41cf-abd1-d573728e6b67)

## Churn Definition in Panel Data
Each property is categorized as “Not Churned” for the initial quarters it sustains and as “Churned” for the quarter it leaves. For example, if a property remains with Airbnb for five quarters, it is labeled “Not Churned” for the first four and “Churned” for the fifth. This approach allows us to discern the contributing factors to property churn, aiding in the prediction of churn probabilities for current-quarter properties.

## Variable Selection and Feature Engineering
Navigating through extensive datasets poses challenges in variable selection and feature engineering. Some variables were intuitively excluded, while others underwent rigorous testing to assess their impact on model variation between churned and non-churned properties. Even if a slight variation was detected, these variables were retained for model development. 
![image](https://github.com/devallasaitej/Airbnb_Targeted_Marketing/assets/64268620/856c0de0-54b9-422b-b966-699c8a08899e)

## Results
![image](https://github.com/devallasaitej/Airbnb_Targeted_Marketing/assets/64268620/bbaf24e4-96bb-42e7-8348-d450673c64f3)
![image](https://github.com/devallasaitej/Airbnb_Targeted_Marketing/assets/64268620/25fb5539-5b47-48f4-8482-ac0a5e34b111)

Among the 3,807 recommended for targeting, 996 properties actually churned. In the holdout data, a total of nearly 2,400 properties churned, and our predictive model captured approximately 40% of these properties. While this percentage might seem modest, the substantial improvement lies in the precision of our targeting efforts. By refining our focus from 24,000 properties to 4,000, we’ve conserved nearly 5/6ths of the total efforts, signifying a noteworthy enhancement in efficiency.
