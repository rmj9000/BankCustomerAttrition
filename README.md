# Bank Customer Attrition Analysis

**Bank Customer Attrition Analysis** is a group project with the aim of identifying reasons why bank customers leave. Our aim to help banks increase their customer retention rates by exploring the reasons and factors that result in customer loss. 

# ![Banner image](images/bannerimagehackathon.png)

## Navigation:
* [ 01: ETL Pipeline](https://github.com/rmj9000/BankCustomerAttrition/blob/main/jupyter_notebooks/01_etl.ipynb)
* [02: Exploratory Data Analysis](https://github.com/rmj9000/BankCustomerAttrition/blob/main/jupyter_notebooks/02_eda.ipynb)
* [03: Heat map](https://github.com/rmj9000/BankCustomerAttrition/blob/main/jupyter_notebooks/03_heatmap.ipynb)
* [04: Hypothesis Testing](https://github.com/rmj9000/BankCustomerAttrition/blob/main/jupyter_notebooks/04_hypothesis-testing.ipynb)
* [05: Data transformation for Tableau](https://github.com/rmj9000/BankCustomerAttrition/blob/main/jupyter_notebooks/05_tableau-data.ipynb)
* [06: Tableau Dashboard](link to be added soon)
* [07: Raw Data](https://github.com/rmj9000/BankCustomerAttrition/blob/main/data/inputs/raw/bank_customer_attrition_insights_data.csv)
* [08: Cleaned Data](https://github.com/rmj9000/BankCustomerAttrition/blob/main/data/inputs/cleaned_bank_data.csv)


## Dataset Content
* The data is sourced from [Kaggle](https://www.kaggle.com/datasets/marusagar/bank-customer-attrition-insights) and contains many routes of inquiry for why customers at banks attrite. 

## Contributers
### Team name : *The Pandas*
### Team members
* Project Manager - [Ronnie](https://github.com/rmj9000) 
* Data Architect - [Kabira Sharpe](https://github.com/ksharpe-byte)
* Data Analyst - [Jane Weightman](https://github.com/Janeweightman)
* Data Analyst - [Shema Rahman](https://github.com/Shema774)

## Business Requirements
According to the finance publication [The Financial Brand](https://thefinancialbrand.com/news/bank-onboarding/the-churn-challenge-four-big-ideas-for-banks-and-credit-unions-looking-to-drive-down-attrition-182528) banks struggle with a 15% attrition rate. Losing customers results in financial damage, and banks should seek to retain as large of a share of customers as they can. Analysing the trends in customer attrition can allow banks to make data informed decisions on building new strategies to increase their customer retention. 


## Hypotheses
### Hypothesis 1: Customers who earn fewer reward points are more likely to attrite.
Reward points often reflect transaction activity and customer engagement. If customers earning fewer points are more likely to leave, it suggests that low engagement is a key driver of attrition. This insight could help the bank identify disengaged customers early and design targeted retention strategies.

#### How we plan to validate:

*Points Earned vs. Attrition*
* T-test: Compares the means of two groups (e.g., attrited vs. existing customers). Assumes normal distribution.
* Mann-Whitney U test: Non-parametric alternative to the t-test. Compares medians and ranks — useful when data isn’t normally distributed.


### Hypothesis 2: Credit card customers with lower credit scores are more likely to attrite.
Lower credit scores may indicate financial instability or limited access to banking services. These customers might leave voluntarily due to dissatisfaction or be targeted for closure by the bank. Understanding this relationship can guide credit policy and customer support strategies.

#### How we plan to validate:

*Credit Score vs. Attrition*
* Correlation analysis: Measures the strength and direction of association between two variables (e.g., credit score and attrition flag).
* Logistic regression: A predictive statistical model that estimates the probability of a binary outcome (e.g., attrition) based on one or more predictors (e.g., credit score).


### Hypothesis 3: Customers with shorter tenure at the bank are more likely to attrite.
We suspect that some customers will hop from bank to bank to take adantage of signup bonuses. Furthermore, if newer customers are more prone to leaving, it may signal issues with onboarding, early experience, or unmet expectations. This insight is crucial for improving customer retention strategies during the first few months of engagement

#### How we plan to validate:

*Tenure vs. Attrition*
* T-test / Mann-Whitney U test: Again, used to compare tenure between groups.
* Histograms / Boxplots: While visualisations themselves aren’t statistical tests, they support statistical interpretation by showing distribution patterns.




## Project Plan
**To aid in planning we used a [Github project board](https://github.com/users/rmj9000/projects/8/views/1)**
![project board](images/projectplanhackathon.png)

* Using a project board allowed us to assisgn tasks to each team member in an organised manner

* Outline the high-level steps taken for the analysis.
* How was the data managed throughout the collection, processing, analysis and interpretation steps?
* Why did you choose the research methodologies you used?

## The rationale to map the business requirements to the Data Visualisations
* List your business requirements and a rationale to map them to the Data Visualisations

## Analysis techniques used
* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques. Justify your response.
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations
* Financial data is highly sensitive and those working with such data have to ensure they are compliant with laws such as the [Financial Services and Markets Act 2000](https://www.legislation.gov.uk/ukpga/2000/8/contents).
* To ensure data privacy we removed the 'Surnames' column of the dataset, as it contains personally identifiable information. 

## Dashboard Design
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 


## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


## Credits 

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- Banner image was made using [Canva](https://www.canva.com/) 



## Acknowledgements (optional)
* A special thanks to all the tutors at Code Insitute and to all our class mates! We wish everyone the best following our final Code Institute project. 
