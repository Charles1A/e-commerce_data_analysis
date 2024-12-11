## Sales data analysis

__Case:__ 

An e-marketing/e-commerce entrepreneur was using a commercial SaaS product to track customer ordering activity and marketing campaign performance.
That software provided basic descriptive analysis of the data, but the client wanted a customized analysis to unlock additional insights.

__Approach:__ 

I cleaned and explored the data set that was provided to me, and considered how different variables related to one another. To quantify those relationships, I computed Pearson's Correlation Coefficient (R) for different variable pairs. I derived a new variable, Days Active, to enable time-based correlations. I created a dashboard to present the analysis in an approachable, updatable way. The principal questions I sought to address were:

Q1: Does the historic number of orders increase the longer someone is a customer?
Q2: Does historic Customer Lifetime Value increase the longer a customer has been active?
Q3: Does Historic Customer Lifetime Value increase with the Historic Number Of Orders?

__Result:__ 

The correlation values enabled the client to evaluate the performance of his e-marketing strategy across different dimensions. 

The graphs below represent some of the analyses I performed for this client.[^1]

<img width="500" alt="Marketing_graphs_quadrants" src="https://user-images.githubusercontent.com/93352455/167263755-1637e8ff-319e-43a5-a479-0cc00dba1b75.png">

| **A:** Boxplot. Shows the spread of the data. | 
| **B-D:** Scatter plots with ordinary least squares trendlines. |

The *R* values (noted above the scatter plots) represent the strength of association between the variable pairs. The maximum possible *R* value is **1**: a perfect positive correlation. 

__Dashboard:__ 

[View live dashboard here](https://order-data-analysis-dashboard.onrender.com/)

<img width="600" alt="Sales-Data-Dashboard" src="https://github.com/user-attachments/assets/fc87fdbd-7f66-4e5c-95e2-8f357371882d">

__Partial Interpretation:__ 

Historic customer lifetime value is not strongly correlated with number of days active. 

Historic number of orders is not strongly correlated with number of days active.

Full remarks and interpretation are available in the code notebook: [E-mail Marketing Data Analysis Notebook](https://github.com/Charles1A/Charles1A.github.io/blob/main/E-comm-data-analysis/E-commerce%20Data%20Analysis%20v1.1.ipynb)

[^1]: The client's data have been altered to maintain confidentiality.
