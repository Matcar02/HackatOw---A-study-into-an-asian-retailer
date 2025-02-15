# Hackatow

In this project, a colleague and I analyzed and predicted customer behavior for an Asian healthcare retailer. The retailer was interested in assessing the effectiveness of its promotions and discounts.

The notebook is divided into three sections:

1. Data Cleaning and Preparation (Wrangling)
2. Promotions and Discounts Insights
3. Time-Series Baseline Sales Forecasting

The objectives and tasks are explained below. The analysis primarily focuses on the performance of selected products.

## Context

- Oliver Wyman has been engaged by an Asian health and beauty retailer to help design a set of promotions in line with their existing promotional offerings and long-term sustainability goals.
- The retailer operates both online and offline (in-store) across multiple countries in Asia. However, our focus is on the Malaysian business unit and its offline promotions.
- The retailer has requested that the team focus on a subset of products within a specific product category.
- To support the Oliver Wyman team, the client has shared multiple datasets to help us understand the current performance of their products and promotions. The client wants to transition to a more data-driven approach, as their category managers previously relied on industry expertise to set up promotions and campaigns without a coherent review of their effectiveness.

## Tasks

As part of the new project team, you are the data and analytics consultant. Senior team members have tasked you with assessing the data shared by the client, conducting exploratory data analysis, and building a simple model to predict baseline product sales.

### More Defined Tasks

#### 1. Data Assessment and Preparation
- The local business teams have shared their entire transaction data history. However, some business teams rely on manual processes to create transaction data, affecting overall data quality.
- Additional details on the datasets provided are available in Appendix A.
- Examine the data and prepare it for further analysis and modeling.
  - Identify data quality issues in each dataset.
  - Assess whether values align with expectations.
  - Evaluate any challenges in joining the datasets.
- The leadership team is also interested in an overall assessment of data quality and recommendations for improvements. As the organization shifts to a more data-driven approach, what enhancements would make the data more useful?

#### 2. Understanding Promotion Performance
- The client wants a quantitative measure to assess the performance of products under promotion.
- To achieve this, we must first establish the baseline sales performance of products without promotion. This will allow us to measure the effectiveness of promotions relative to the baseline.
- A model must be trained to predict baseline sales without promotional activity. Key considerations include:
  - Whether and how to include days with active promotions in the training data.
  - Identifying external factors that influence consumer behavior beyond promotions (e.g., weekends, seasons, holidays, natural disasters) and how to incorporate them into the model (binary, numerical, categorical variables, etc.).
  - Capturing long-term trends related to the product.
- A common metric for measuring promotion effectiveness is elasticity—the relationship between the additional sales uplift and the discount offered. The client is interested in using elasticity as a consistent promotion performance metric.

**Note:** Due to confidentiality agreements, we cannot share the data.

Hope you enjoy this project!

