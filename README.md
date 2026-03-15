F1 Sports Analysis: Driver Risk Profiles and Team Reliability

This project presents a data-driven statistical and machine learning analysis of Formula One, focusing on two key dimensions of performance: team reliability and rookie driver risk profiling. Using over 35 years of historical Formula 1 data, the study explores how race outcomes are influenced by grid positions, driver consistency, crash history, and junior-series achievements.

Team Reliability Analysis

The first objective is to understand what makes a Formula 1 team reliable over time. Since regulations, engines, and car designs change frequently, reliability was evaluated across multi-year eras rather than single seasons. Exploratory Data Analysis (EDA) was conducted to compute metrics such as mean starting and finishing positions, qualifying performance, points scored, and DNF (Did Not Finish) rates.

A key performance indicator, grid improvement per race, showed that drivers gain approximately 1.8 positions on average, indicating the impact of race pace beyond qualifying. Pearson correlation analysis revealed a moderate positive relationship between starting and finishing positions, confirming that grid placement significantly affects race outcomes. A custom reliability model was then developed to calculate team consistency across eras, highlighting trends such as improved performance for Ferrari and sustained reliability for Mercedes.

Rookie Driver Risk Clustering

To evaluate recruitment risk, K-Means clustering was applied to junior-series statistics of 125 drivers. Features included crash frequency, DNFs, wins, podiums, championships, and total race participation. After normalization using StandardScaler, drivers were grouped into three risk clusters representing low, moderate, and high risk. Cluster profiles were interpreted using crash rates, DNF rates, and success metrics, enabling teams to estimate the potential reliability of rookie drivers before their Formula 1 debut.

Rookie Point Prediction

Finally, a logistic regression model was built to predict whether rookie drivers would score championship points in their debut season. The dataset was preprocessed through median imputation, label encoding, and feature scaling. Using a 75–25 train-test split, the model was evaluated using accuracy, precision, recall, F1 score, and ROC-AUC. Results indicated that junior-series wins, podium finishes, and race experience positively influence debut success, while high DNF rates reduce scoring probability.

Conclusion

By integrating correlation analysis, clustering, and classification techniques, this project demonstrates how data science can uncover hidden performance patterns in motorsport. The findings provide a quantitative framework for evaluating team consistency, driver risk, and rookie potential, offering valuable insights into the factors that shape championship-winning Formula One teams.
