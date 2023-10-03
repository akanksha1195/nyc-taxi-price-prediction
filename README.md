# nyc-taxi-price-prediction

![image](https://github.com/akanksha1195/nyc-taxi-price-prediction/assets/115442156/455a4b33-d271-4ebf-99c6-0093afa6b6fc)
1. Introduction

   In this project centered around New York City's significant traffic challenges and the popularity of taxis as a mode of transport, we aimed to predict taxi trip durations using the "NYC taxi trip duration dataset". With NYC's enormous population of approximately 18 million people, traffic congestion is a pressing issue, making accurate trip duration predictions essential for travelers to plan their journeys effectively. My project encompasses insightful visualizations illustrating the relationship between trip duration and various variables. Additionally, I explored how mean passenger count, total trips, distance, and duration fluctuate across different weekdays. To enhance the predictive power of the models, we employed extensive hyperparameter tuning techniques alongside machine learning models, including linear regression and decision tree. My project's journey begins with a thorough dive into data preprocessing, paving the way for enhanced insights and predictions.

2. Data Preprocessing

   During the data preparation phase, I conducted a series of crucial operations to refine the dataset. The distance is calculated between pickup and dropoff locations by computing the geographical distance based on latitude and longitude coordinates. Additionally, I transformed the pickup and dropoff date-time information into a datetime format.
   To further enhance the dataset's suitability for machine learning, I binned the time data into six distinct bins, allowing for a more granular analysis of temporal patterns. Additionally, several preprocessing steps were meticulously applied to the data, ensuring its readiness for utilization in my machine learning models. These preparatory measures laid the foundation for more accurate and insightful predictions.

3. Exploratory Data Analysis
     The exploratory data analysis unveiled compelling insights within the dataset. It became evident that the majority of cab rides involved one or two passengers, indicating a prevalent usage pattern. Surprisingly, Fridays saw more cab usage than Mondays, hinting at shifting travel behaviors toward the end of the week. Furthermore, the analysis revealed that evening pickups and nighttime drop-offs were most frequent, with relatively lighter traffic in the early morning hours. The histogram emphasized the preference for evening and nighttime rides. Vendor id: 2 attracted a larger customer base compared to Vendor id: 1, suggesting a preference among passengers. Trip durations peaked on Thursdays and Fridays, particularly during the afternoon and evening hours, likely due to increased traffic. These findings offer valuable insights into travel patterns and customer preferences, providing a solid foundation for informed decision-making and predictive modeling in the project.

4. Model Building
     In the model-building phase, I conducted a series of essential steps to construct accurate predictive models. Firstly, I applied standard scaling to the dataset, ensuring that features were appropriately scaled for modeling. Subsequently, I partitioned the dataset into training and testing subsets, facilitating robust model evaluation. The approach involved employing both linear regression and decision tree algorithms. I meticulously fine-tuned model parameters using hyperparameter tuning techniques, optimizing their performance. These steps showcase the dedication to rigorous model development and data-driven decision-making in this project.

5. Model Evaluation
      In the model evaluation phase, I employed a comprehensive approach to fine-tune the decision tree algorithm. Specifically, we conducted hyperparameter tuning by meticulously optimizing the tree's depth, setting it to 11. This meticulous tuning process aimed to enhance the model's performance and predictive accuracy. As a result of the efforts, we successfully trained the model and achieved a commendable accuracy of 62% on the test dataset. These results underscore our commitment to precision and excellence in model development and evaluation within this project.


