**COMPARATIVE ANALYSIS OF ESG vs. FINANCIAL INDICATORS ON PREDICTING BETA**

**Abstract**
This research investigates the use of Environmental, Social, and Governance (ESG) performance and financial indicators in predicting companies' future financial outcomes. Specifically, we compare the significance of 2 Bloomberg ESG scores with 9 traditional financial ratios in forecasting stocks' betas, leveraging Random Forest Classifier machine learning algorithms. Additionally, we provide valuable insights into the relative importance in each of the 11 Global Industry Classification Standard (GICS) sectors, differentiating their predictive power in bullish and bearish market conditions.
The study aims to address a fundamental question: Does prioritizing "doing good" through ESG practices align with "doing well" financially?

**Methodology**

Machine learning algorithms were chosen as the core methodology for this research. The main reason for the choice of methodology is their ability to identify patterns among variables in predictive tasks. This choice was driven by the need to explore potential patterns between ESG scores and beta, enabling a comprehensive investigation of their relationship.
To build machine learning algorithms, two types of variables were identified: features and targets. In this case, Beta was chosen as a target variable whereas feature variables included:
![image](https://github.com/DKodirova/ESG-vs.-Financial-Indicators-in-Predicting-Market-Returns/assets/141365455/a98200b3-8549-4787-8470-8422f704da8a)

Given this study’s objective of predicting beta's class (i.e. beta’s range) rather than estimating its precise numerical value, I decided to use a classification model that would forecast beta’s class, which is one of the listed in Figure 2. Because market performance varies, classification of betas can be different in each year. 
The Random Forest Classifier model was selected as the most appropriate from the list of potential algorithms. It is an ensemble learning model that combines multiple decision trees to improve accuracy and robustness, making predictions based on majority voting or averaging from individual trees.

**Results**

The model was applied to both the general dataset and individual industries and market types. 
The initial application of the model to the general dataset yielded convincing results, with the model achieving an accuracy score of 93%. The model was trained using 1420 companies and tested on other 356 companies.

By analyzing the feature importance breakdown of the model in Figure 5, given below, we observed that ESG Score and ESG Disclosure Score  played a discernible role in predicting returns, contributing 7.6% and 6.3% importance, respectively. Although these values are slightly lower than the average mean of importance for all other financial indicators (8.0%), it is noteworthy that ESG measurements showcased their potential value as predictive factors.

To gain deeper insights, we examined the breakdowns for 11 GICS sectors and 2 market types, as presented in the accompanying graphs.

**Discussion**

The findings from this analysis revealed interesting patterns: there were instances where ESG measurements surpassed traditional indicators in terms of usefulness. A notable example was observed in the Consumer Discretionary sector during bearish markets, where the ESG Disclosure Score exhibited the highest importance. Remarkably, even during bullish market conditions, this score remained among the top three in terms of importance.

Another interesting discovery was that in 7 out of the 11 industries - Communication Services, Financials, Information Technology, Industrials, Consumer Discretionary, Energy, and Utilities-  ESG Measurements proved more valuable in bearish markets than in bullish ones. This suggests that ESG could play a more crucial role in decision-making during uncertain and weak market periods, particularly for dynamic industries. 

In conclusion, while ESG information is not a magical source  for predicting financial returns, our findings indicate that it holds significant potential and should be seriously considered when assessing company performance, especially during challenging times such as bear markets. Embracing ESG as an additional dimension in the evaluation process can enhance decision-making and lead to a more comprehensive understanding of a company's prospects and resilience in varying market conditions.



