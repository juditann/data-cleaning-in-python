# Audible: Overview of the Audibooks Market

## Dataset

The dataset for this project can be found on [Kaggle](https://www.kaggle.com/datasets/snehangsude/audible-dataset/data) (licensed under CC0: Public Domain).

The dataset consists of audibooks released from 1998 to 2025 (pre-palanned release), which was web-scraped by the dataset's author from the Audible India's website.

## Objectives
The main objective of this project is:

> To perform data cleaning techniques and data analysis to get an overview of the current Audiobooks market.

To achieve this objective, the above was broken down into the following sub-objectives:
1. To discover data quality issues, such as missing data or duplicated data.
2. To perform data cleaning and fix the identified data quality issues.
3. To perform in-depth exploratory data analysis using the cleaned dataset.

## Main Insights 

From the exploratory data analysis using the cleaned dataset, we found the following observations:
- The release of audiobooks on Audible shows an exponential growth, with the largest number of books released happening in the year interval 2022-2023.
  - This rise in the number of released books within the year interval 2022-2023 could be related to people going back to work after the pandemic, which could have resulted in an increase in the demand of audiobooks due to things such as, commuting to work or travelling to other cities/countries.
  - Eventhough the number of released books has been increasing exponentially, the number started to increase drastically at around the year 2018 onwards. This might have been due to the rise in popularity of Audible in the late 2010s (Hilton, 2023).
  - Based on this analysis, we could carry out demand forecasting to estimate future customer demand and understand how releasing audibooks could make an impact on the business.
<p align="center">
  <img src="/assets/vis1.png" />
</p>

- There is a positive correlation between an audiobook's duration and price. However, correlation doesn't mean causation. Other factors that could affect an audiobook's price could be the popularity of a book's author, the popularity of a narrator, whether an audiobook was translated, and any additional offers/sales placed on the book by Audible or the book's publisher.
<p align="center">
  <img src="/assets/vis2.png" />
</p>

## Business Metrics

This dataset could be used alongside other datasets to calculate business metrics that are of interest to the publishing industry. However, this dataset by itself is not enough to calculate business metrics. 

Some business metrics that we could calculate using this dataset, if we have other datasets as well, are:

- **Revenue per title:** this allows publishing companies to understand which book genres and specific titles generate the most profit. By understanding this, companies can understand their audience and their interestes better, which would provide project managers and their teams more information for better resource allocation.
  - *Data missing:* In order to calculate the revenue per title in this situation, we would need data on the **number of sales** each title has generated. The number of ratings give us an idea on the minimum number of sales that each title has generated, however, this number is not representative of the total sales for each book.
- **Average sales per author:** This provides us with information on an author's work's performance. By carrying out long-term performance analysis, we can compare an author's performance against the company's competitors. Apart from that, this metric allows companies with their long-term planning by deciding their marketing strategies and by deciding their book realease schedules to optimise sales.
  - *Data missing:* To calculate this metric, we would need the **number of sales** for **all the books** released by a specific author. 
