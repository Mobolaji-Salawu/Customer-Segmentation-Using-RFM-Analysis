# Customer Segmentation Using RFM Analysis
This purpose of this project is to segment the customers of a fictitious company into various customer segments using the RFM analysis method. The datasets and Jupyter notebook used in this project are included in this repository.
## Introduction
Not all customers are the same. Oftentimes, different types of customers have different needs and motivations. Hence, a single approach to recruiting and retaining customers often will not yield the desired result for all customers.

Customer segmentation is the process of grouping customers into specific groups based on shared characteristics and/or behaviors. The goal is to ensure that companies can easily tailor marketing, service, and sales efforts to the needs of each group.

**RFM analysis** is an effective customer segmentation method that is used to rank and segment customers based on their past purchase behavior over a time period. It is anchored on three core dimensions of customer behavior (and this is where the "RFM" acronym is derived from):
* ***Recency*** – how recently a customer made a purchase
* ***Frequency*** – how often has the customer made purchases over a specified period of time
* ***Monetary Value*** – what is the total value of these purchases over the defined time period
## Methodology
### Data
The RFM analysis was done using the customer transaction data of a fictitious company.
### Python Libraries
The following Python libraries were used in this project:
* Numpy – For multi-dimensional array, matrix data structures and, performing mathematical operations
* Pandas – For storing and manipulating structured data. Pandas' functionality is built on NumPy
* Matplotlib - For creating data visualization
* Seaborn - For creating visualization. Seaborn's functionality is built on top of Matplotlib
* datetime - For working with dates and times
### Process
The main stages of the project is summarizsed in the flow chart below:
![image](https://github.com/Mobolaji-Salawu/Customer-Segmentation-Using-RFM-Analysis/assets/80423645/dea9f756-0bd3-4fb9-ad5e-b8ec8f722685)
## Results
Using the RFM analysis method, the customers were grouped into various customer segments based on the how recent a purchase was made (*Recency*), how many times purchases were made over the two-year period (*Frequency*), and the total amount purchased over the same time frame (*Monetary Value*). The segments were ranked, from the highest value to the least value customer segment.

![Customer Segmentation](https://github.com/Mobolaji-Salawu/Customer-Segmentation-Using-RFM-Analysis/assets/80423645/c501feea-ce7c-4bf4-b74f-81473da389f6)
[^1]: Credit to [Connectif](https://connectif.ai/en/blog/what-are-rfm-scores-and-how-to-calculate-them/) for the customer segments used.
