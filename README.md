# Analysis of Client Disputes for Yellevate
Period covered - 2020 to 2022

## Contents

- [Problem Statement](#problem-statement)
- [Data Analysis Goals](#data-analysis-goals)
- [Methodology](#methodology)
   - [Excel](https://drive.google.com/drive/folders/1volhDIgOOEKsDRPH_Adb47j6hFbCkz9x?usp=sharing)
   - [SQL](https://drive.google.com/drive/folders/1volhDIgOOEKsDRPH_Adb47j6hFbCkz9x?usp=sharing)
   - [Analysis Limitations](#analysis-limitations)  
- [Findings](#findings)
  - [Observation 1](#observation-1)
  - [Observation 2](#observation-2)
  - [Observation 3](#observation-3)
  - [Observation 4](#observation-4)
  - [Observation 5](#observation-5)
- [Dashboard](#dashboard)
- [Conclusion](#conclusion)
- [Recommendation](#recommendation)
- [Annex 1](#annex-1)
  - [Excel](https://drive.google.com/drive/folders/1volhDIgOOEKsDRPH_Adb47j6hFbCkz9x?usp=sharing)
- [Annex 2](#annex-2)
  - [SQL](https://drive.google.com/drive/folders/1volhDIgOOEKsDRPH_Adb47j6hFbCkz9x?usp=sharing)
- [Yellevate Final Report in PDF](#yellevate-final-report-in-pdf) 
- [Yellevate Final Report in Slides](#yellevate-final-report-in-slides)
- [Contributors](#contributors)

## Problem Statement

Yellevate has been struggling with client disputes for the past few years*. This has been a huge financial
burden for the company, Statistically, nearly 20% of the conflicts raised against the Company resulted in a
payment opt-out as it led to an approximate 5% annual loss of revenue (in USD).

Our team were tasked to identify their causes and come up with actionable strategies to solve them.

*disputes - clients expressing dissatisfaction with the company’s services and refusing to pay for them

## Data Analysis Goals

- Use the given raw data, transform and clean the data in order to generate a useful insight.
- Discover patterns in the data, determine the root cause of the disputes and provide
recommendations or points of improvement.

## Methodology

Our team used the following analytics tools in order to analyze, generate insights, clean and create
a visualization of the processed data. By using these tools, we were able to investigate thoroughly each of
the problem points that the company were facing.

We validated and scanned the dataset prior to performing a specific task in Excel and SQL, our team
checked for “nulls”, “misspelt information”, the formatting and any incomplete or inaccurate data.

- Excel
  
  A. Created arithmetic formulas and simple functions
  
  B. Used pivot table to group and process further the data
  
  C. Created charts and graphs in order to easily understand and visualize the analysis

See [Annex 1](#annex-1) for additional reference

- SQL

  A. Used PostgreSQL as our SQL dialect and imported the file into its server

  B. Used common statements and commands (e.g., mathematical and aggregate functions)

  C. Used CRUD operators to clean the data *this portion is optional since the dataset contains a
     minimum number of fields and it is still manageable to work on the given information

See [Annex 2](#annex-2) for the detailed process

## Analysis Limitations

Our team performed the analysis with the following limitations -

1. No evidence of the reason for disputes

2. The analysis covers the timeframe from 2020 to 2022

3. Conclusion is limited only based on the data and important assumptions provided -

   - All the services Yellevate was hired to do were fully completed.
     
   - The quality of the services provided is not the main driving reason for these invoice
     disputes.
     
   - Yellevate management believes most disputes are the result of contract technicalities or
     clients thinking they can get away with not paying for the services.
     

## Findings

- ### Observation 1

  ![image](https://github.com/Wilmertjuntado/Yellevate-Analysis-Report/assets/64041142/e0398541-607e-42d5-896d-2fa892856c76)

  The average time in which invoices are settled is 26 days. There is no significant correlation between the
     average processing time to settle per country versus the number of disputed invoices.

- ### Observation 2

  ![image](https://github.com/Wilmertjuntado/Yellevate-Analysis-Report/assets/64041142/13a288fa-8844-4b54-8424-2dd11df8042f)

  ![image](https://github.com/Wilmertjuntado/Yellevate-Analysis-Report/assets/64041142/3d99e738-1374-45f3-b920-0c8675881612)

  Processing time for the companies to settle disputes is 36 days (beyond the 30-day due date). The United States
      has the longest processing time to settle disputes (41 days) followed by Russia (38 days) and Spain (37
      days). China and France, on the other hand, have the least processing time (34 days).

- ### Observation 3

![image](https://github.com/Wilmertjuntado/Yellevate-Analysis-Report/assets/64041142/ead9e810-fab3-47de-aeff-5645bd293ae5)

Total Revenue (Invoice Amount): 14,770,318 USD *gross amount
Dispute Lost (Invoice Amount): 690,167 USD
Disputed (Invoice Amount): 3,748,744 USD

101 out of 571 disputes received by the company were already treated as dispute lost (17.69% of the
total number of disputes).


- ### Observation 4

![image](https://github.com/Wilmertjuntado/Yellevate-Analysis-Report/assets/64041142/a691d090-d563-49eb-9278-84997afa3f73)

The percentage of revenue lost from disputes is 4.67% 690, 167 USD out of 14, 770, 318 USD. France is the
largest among the list covering almost 76% of all the revenue losses, followed by Russia and China.


- ### Observation 5 

![image](https://github.com/Wilmertjuntado/Yellevate-Analysis-Report/assets/64041142/9b8d2186-f699-48ff-adee-bf550d38f0bc)

![image](https://github.com/Wilmertjuntado/Yellevate-Analysis-Report/assets/64041142/429b8ef8-3c77-4bb8-820e-0b4a92bc114a)


The country where the company reached the highest losses from lost disputes (in USD) is France,
covering 76.25% of all the dispute losses followed by Russia at 11.78%, China at 6.18%, the United States at 3.32%, and
Spain 2.47%.


## Dashboard

![image](https://github.com/Wilmertjuntado/Yellevate-Analysis-Report/assets/64041142/02639ae0-c666-4fbc-bc9b-6fb0bc19bc6f)


## Conclusion

In summary, we observed that there is a 4.67% or 690, 167 USD of revenue lost from the disputes, out of
the 4.67% revenue lost, we have France as the first country on the list (526, 264 out of 690,167 USD),
followed by Russia (81,291 out of 690,176 USD) and China (42,630 out of 690,167 USD).


Yellevate’s client France dragged the total percentage of disputes lost contributing to a whopping 75.25%
of all the dispute losses. Some of the factors of France’s performance can be due to the effect of the 2020
pandemic, this worsened the country's economy in 2020 and pushed the economy further down until the year
2021.

Source: [Covid-19 pandemic pushes French economy into deep recession (france24.com)](https://www.france24.com/en/europe/20210129-covid-19-pandemic-pushes-french-economy-into-deep-recession?fbclid=IwAR1qaosydEHxrcidJ5_uL6Fso6Vna1T1I7uyHP6hHD2MfkN8MH3vHyZZ9x8)


The average time in which invoices are settled is 26 days and the processing time for the companies to settle
disputes is 36 days which is beyond their normal 30-day due date. This insight is somewhat alarming and
the company, Yellevate, should revisit their existing policies/contracts or any related procedures/workflow.

*Disclaimer: If time allows and the stakeholder permits, we can wait for more data in order for our team to
process a more detailed and evidence-backed analysis.*

## Recommendation

1. Stretch the payment due date once a common pattern of dispute has been detected (e.g., grace
      period of another 5 to 10 days) and provide a manageable timeline to give enough time on
      struggling countries to settle any pending balances.

2. Provide payment plan option at the onset of the contract and choice to switch to another
      payment scheme (e.g., instalment/payment on credit/ flexible terms of payment).

     Win-win situation
      This resolution will benefit both parties due to the following reasons:

     - The client can still treat these transactions as part of their payable/expenses for tax benefit
        purposes

     - Yellevate can still collect revenue/receivable at some point in time
    
       
**Additional Points of Improvement or Suggestion**

3. Include a 'penalty' provision in service agreements to reinforce early or on-time payment
 
4. Include discounts/rewards in the contract to attract early payments
 
5. Provide provision for reimbursements/money-back guarantee on “mistaken” services rendered
 
6. Notifying the vendor – The vendor must be notified in writing within xxth1 calendar days from the
      receipt of the invoice.
     
     - Notify the vendor on time
    
     - Send an email notice and include the invoice as an attachment
    
     - If the vendor fails to respond on the nth time, treat this transaction right away as an outright expense (payment failure or revenue lost from dispute)
 
7. Be open to any communication and make necessary adjustments if needed. Creating a culture of
      empathy, compassion and transparency is one of the virtues a company should practice in case
      a black swan event happens.
     

## Annex 1 
- [Excel](https://drive.google.com/drive/folders/1volhDIgOOEKsDRPH_Adb47j6hFbCkz9x?usp=sharing)


## Annex 2 
- [SQL](https://drive.google.com/drive/folders/1volhDIgOOEKsDRPH_Adb47j6hFbCkz9x?usp=sharing)


## Data Analysis


```sql

CREATE TABLE yellevate_invoices (
country varchar,
customer_id varchar,
invoice_number numeric,
invoice_date date,
due_date date,
invoice_amount numeric,
disputed numeric,
dispute_lost numeric,
settled_date date,
days_settled integer,
days_late integer
);

--Ensure that the fields were properly reflected
SELECT * FROM yellevate_invoices;

--Import the file
COPY yellevate_invoices FROM 'D:\Download Folder\Yellevate Invoices.csv'
WITH CSV HEADER;

--Created a back up file

CREATE TABLE yellevate_backup AS
SELECT * FROM yellevate_invoices

--Average processing time for settling invoices:
SELECT ROUND(AVG(days_settled)) AS avg_days_settled
FROM yellevate_invoices
WHERE settled_date IS NOT NULL;

--Average processing time for settling disputes:
SELECT ROUND(AVG(days_settled)) AS average_days_to_settle_dispute
FROM yellevate_invoices
WHERE disputed = 1 AND settled_date IS NOT NULL;

--Percentage of disputes received by the company that were lost From the :
SELECT ROUND
(COUNT(CASE WHEN dispute_lost = 1 THEN 1 ELSE NULL END) / COUNT(*)::numeric * 100, 2) AS
dispute_loss_percentage
FROM yellevate_invoices
WHERE disputed = 1;

--Other alternative
SELECT ROUND(100.0 * SUM(dispute_lost) / SUM(disputed), 2) AS percentage_disputes_lost
FROM yellevate_invoices
WHERE disputed = 1;

--Percentage of revenue lost from disputes:
SELECT
SUM(invoice_amount)
FROM yellevate_invoices

WHERE dispute_lost = 1;

--Correct Answer
SELECT
ROUND(100.0 * SUM(CASE WHEN dispute_lost = 1 THEN invoice_amount ELSE 0 END) /
SUM(invoice_amount), 2) AS percentage_disputes_lost
FROM
yellevate_invoices;

--Country where the company reached the highest losses from lost disputes:
SELECT country, SUM(invoice_amount * dispute_lost) AS total_loss
FROM yellevate_invoices
WHERE disputed = 1
GROUP BY country
ORDER BY total_loss DESC
LIMIT 1;

--Data Cleaning (removed duplicates *if there's any , sorted settled_date)
CREATE TABLE yellevate_clean AS
SELECT DISTINCT customer_id, country, invoice_amount,settled_date,disputed,
dispute_lost FROM yellevate_invoices
ORDER BY settled_date DESC;

```

## Yellevate Final Report in PDF 
- [Click link here](https://drive.google.com/file/d/12a56a8_WX3U_Hnyu_9LglWkILuIWBhE-/view?usp=sharing)

  
## Yellevate Final Report in Slides 
- [Click link here](https://drive.google.com/file/d/1xO3tZ_ysfvh_jXLb1HTuAgpeSktH5dqx/view?usp=sharing)


## Contributors

- Batarao, Jessa Marie
- Genisera, Rochelle
- Juntado, Wil
- Llego, Rixer
- Nardo, Mark Gideon
  



  
  
   
