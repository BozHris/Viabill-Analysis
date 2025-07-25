# ViaBill Customer Analytics

We have a database containing info on users, transactions, installments and merchants. 

**1. Portfolio overview for the last 12 months**

We can see that for the last 12 monhts we have had a significant increase in new customers, while the numbers dropped in October(650) the almost doubled in November(1175). This could be due to seasonality or other factors however looking at global shopping trends they tend to increase during the fall months, but in any case this growth should be monitored carefully. 

<Figure size 1000x500 with 1 Axes><img width="989" height="490" alt="image" src="https://github.com/user-attachments/assets/ea505498-64dd-4c93-9bdc-be328308787e" />


Following up with the Active Customers and Transactions Volume and Amount overview we see a drop in transactions during October but they are steady again in November having more than doubled. 
<Figure size 1000x500 with 2 Axes><img width="989" height="495" alt="image" src="https://github.com/user-attachments/assets/5d3390a3-debb-4670-9402-b30c1d18e05e" />

<Figure size 1000x500 with 2 Axes><img width="989" height="495" alt="image" src="https://github.com/user-attachments/assets/bce73210-bea1-44ef-bb05-4c8103b6ce3d" />


Looking at the installment count we can see tha users choose to pay in 4 installments 75% of the time
<Figure size 800x500 with 1 Axes><img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/75177f01-e8cc-437b-8863-f151f866284f" />

To correlate this with the top merchant categories we see that Electronics is the most popular followed by Fashion
<Figure size 800x500 with 1 Axes><img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/50e9e9a8-eaa5-4770-9493-adde7b8f9eea" />

**2. Payment Analysis**

Regarding the Day Past Due Analysis we can see that: 
Percentage of installments paid on time: 19.15%
Installments with DPD 1–5 days: 111646 out of 214828 (51.97%)
Installments with DPD ≥ 90 days: 41664 out of 214828 (19.39%)
<Figure size 800x500 with 1 Axes><img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/e92bd114-9036-4368-9a7a-722b4ce4ea04" />

Looking a bit deeper with the DPD rate, we can see that most transactions are related to installments not that overdue, +90% of transactions have a rate of 0-5% DPD rate.
<Figure size 800x500 with 1 Axes><img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/85ed18da-16f2-4f0c-9c25-f331eb49b1bc" />


Looking at the DPD90( 90 days overdue) 
<Figure size 800x500 with 1 Axes><img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/633999a6-e684-4b06-b2de-ad0184a78f1b" />
<Figure size 800x500 with 1 Axes><img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/887f6727-ad66-4b94-93d6-a50c0a50f3ea" />
<Figure size 1000x500 with 1 Axes><img width="989" height="490" alt="image" src="https://github.com/user-attachments/assets/f67d691e-a5bb-4871-863c-f3e7b803c7c2" />


**3.Vintage Analysis**

Looking at DPD90 many curves peak at month 0 to 2, indicating that most users who are bad they do so early. 

Some older vintages have higher spikes: E.g., 2022-05 and 2022-03 show sharp peaks at month 0–2 reaching over 60–80%.

Newer vintages are more stable. Most curves from 2024 onward show lower early-month DPD90 rates, staying mostly under 20%, suggesting improvement in credit quality or tighter control.

Cohort tails are long but flat:
After the initial few months, most curves flatten, meaning little new delinquency occurs after the first 5–10 months.
<Figure size 1200x600 with 1 Axes><img width="1191" height="807" alt="image" src="https://github.com/user-attachments/assets/d32fce73-9f9a-4962-9a55-e61e4e61ef45" />



