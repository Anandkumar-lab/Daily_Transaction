# Daily_Transaction
# About Dataset
The **Daily Transaction** dataset contains information on dummy transaction made by an individual on daily basis includes data on the product that were the payment mode of each transaction and the source of each record (EXpense/income)

This dataset can be used to analyzed purchasing behavior and money management forcating expenses and optimazing saving and budgeting strategies. The dataset is well-suited for data analysis and machine learning,it can be used to train predictive models and make data-driven decisions.

## Column Descriptors
- **Date**: The date and time when the transaction was made
- **Mode**: The payment mode used for the transaction
- **Category**: Each record is divided into a set categories of transaction
- **Note**: A berif description of the transaction mode
- **Amount**: The transaction amount
- **Income/Expense**: The indicator of each transaction representing either expense or income
- **Currency**: All transaction are recorded in offcial currency of india
<img width="859" height="547" alt="Image" src="https://github.com/user-attachments/assets/624d2de4-a42d-435a-8977-2a989aee2fc7" />

#### Description of the Chart:
**Title:** Distribution of Transaction Amounts

**X-axis:** Represents the transaction amount values.

**Y-axis:** Represents the frequency of those amounts (i.e., how often each range of amounts appears).

#### Observation:

The distribution is highly right-skewed (positively skewed).

Most transactions occur at very low amounts (close to zero).

There are few high-value transactions (outliers) extending beyond 50,000, even reaching above 200,000.

This long tail suggests the presence of rare, large transactions which can significantly affect mean-based metrics.

#### Key Insights:
Majority of transactions are in the low range.

There may be outliers or fraud indicators in the high-amount region.

Log transformation may be useful to normalize this distribution for modeling.
<img width="571" height="472" alt="Image" src="https://github.com/user-attachments/assets/e211fb7f-0713-49ad-abe5-5d85bf62553d" />
#### **Top 3 Transaction Amounts – Insights**
₹1000.0 is the Most Frequent

With a frequency of nearly 195, this is clearly the most common high-value transaction.

Likely represents recurring big payments like rent, tuition, loan EMIs, or salary transfers.

₹20.0 and ₹30.0 Are Also Popular

₹20.0 ≈ 125 transactions

₹30.0 ≈ 120 transactions

These likely indicate small purchases (snacks, fares, digital services, etc.).

Skew Toward High and Low Values

There’s a noticeable gap in mid-range values—suggesting transaction behavior is bimodal:

Either very small day-to-day spending

Or large, planned financial transactions

<img width="1005" height="614" alt="Image" src="https://github.com/user-attachments/assets/ca3698bf-541f-433a-af8e-82047ee51c2f" />

#### **Insights from the Chart:**
- Food Dominates Transactions:

Food has by far the highest transaction count—well over 900.

Indicates a significant portion of daily or recurring spending goes to food-related purchases.

- Transportation is Second:

Around 300 transactions.

Suggests commuting, fuel, or ride-sharing is a major expense area.

- Household & Subscriptions:

Household `(175)` and Subscription services `(150)` also have noticeable presence.

Could relate to utilities, rent, internet, streaming platforms, etc.

- Others (Mid-range):

Categories like Investment, Other, and Health fall in the 100–130 range.

Possibly reflect periodic or planned expenses.

- Low-frequency Categories:

Apparel, Family, and Salary have the fewest transactions (< 75).

"Salary" likely refers to income transactions, which occur less frequently.
<img width="989" height="1489" alt="Image" src="https://github.com/user-attachments/assets/32e5476b-484b-4268-bc18-8fb2771d171b" />

### **Top 10 Case Transaction (Top Plot)**
  **Key points:**


   - Food dominates with 450+ transaction
   - Transortation follows(255) a distant seconds.
   - Category like Household,other,health family,and Apparel taper down gradually.
   - Feastivals Beauty and Maid have the fewest cash transaction

### **Interpretation**
  - Cash is mostly used for daily essentials like food,travel,household,goods.
  - Ii is used for one-time or expenses (e.g. beauty,festivals).

### **Top 10 Saving Bank Transaction (Middle Plot)**
  **Key Point**
  - Food again leads (350) even for bank transaction.
  - Category like Subscription Salary,Transportatin,and Household follow.
  - Gift and Apparel are at the lower end.
### **interpretatin**
  - Saving accounts are used for both daily needs and recurting payments like Subscription and salary deposits.
  - More structured regular financial activities are likely linked to this mode.

### **Top 10 Credit Card Transaction (Bottom plot)**
  **Key ponits:**
  - Much lower volume overall (highest-40).
  - Top category Food,Household,Subscription,Health.
  - Uncommon use for Culture,Gift,and Other.
### **Interpretation**
 - credit careds are used less frequently.
 - Mostly reserved for larger discretionnary expenses like subscriptions household or health.
 - May refect contorlled or intentional use of credit.
 
<img width="667" height="504" alt="Image" src="https://github.com/user-attachments/assets/d7b82fb1-b028-49cb-9041-4e17b8a64d32" />

### **Saving Bank Key Insight**
1. **Milk 1lit** again leads making up a massive 55.4% of all saving bank transaction trend consistent with previous chart transaction.
2. The second-highest share is **from workplace** at 14.4% indicating salary or reimbursement inflows.
3. Other noteworthy category include:
  - **1lit** - 5.7%
  - **Mobile Service provider recharge with** -4.7%
  - **Half lit Milk** - 4.0%
  - **Data Booster pack** 3.7%
  - **From Family and Interset paid** - 3.0% each
  - **6 Eggs** - 3.0%
  - **Farewell contribution** - 2.7%

<img width="704" height="470" alt="Image" src="https://github.com/user-attachments/assets/bf57e90a-fa4f-493c-bc77-ecc77c584639" />

### **Chart Title**
**Income and Expense Transaction**
 - Clearly describes what the chart represnts a comparison of the number of transaction across different types.

#### **X-axis:Income/Expense**
Show the three category:
 - Expense
 - Income
 - Transfer-Out
Each label is clear short and directly tied to the type of financial activity.

#### **Y-axis: Count**
Represents the number of transaction for each category.
 - The height of each bar show how often that transaction type occurred.
 - The Y-axis has a logical scale (0 to 2000+) that markes the difference between category visible.

#### **Bar Heights (Insight)**
1. **Expense**
 - Height bar in the chart.
 - Nearly 1900+ transaction showing this is the most ferquent activity.
 - Suggest daily or repeated small-value spending (e.g. milk,food,travel).
2. #### **Income**
 - Much shorter bar than expenses.
 - Around 150 transaction likely montly salary or reimbursements.
 - indicates income is less frequent but possibly higher in amount.
3. #### **Transfer Out**
 - Smallest bar
 - About 30-50 transaction possibly wallet or account transfers.
 - Rarely used compared to expense and income.

<img width="881" height="547" alt="Image" src="https://github.com/user-attachments/assets/dfd2bd29-3080-409c-8b05-fb8d763b1487" />

### **Decription:**
 - Y-Axis(Amount): Represent the values of the transction amount.
 - X-Axis(Statistic): Contains two category `Mean and Median`.
 -  The Mean bar is singnificanty taller than the Median bar indicating.
    - The Mean transaction amount is much higher than the median.
    - This suggests the data is positively skewed( right-skwed),likely due to a few vwry large transaction the Mean.
 - The Median bar represent a more typical transaction amount that is not affected by extreme values.

<img width="856" height="547" alt="Image" src="https://github.com/user-attachments/assets/57333b8f-1814-4239-aac4-a29ecc5ba0e6" />
