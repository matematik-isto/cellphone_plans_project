# Cellphone plans analysis
## 📌 Summary
Megaline offers two prepaid plans: Surf and Ultimate. Comercial department desires to know which planes generate more profit to be able to adjust advertising budget.
## 🗃️ Datasets
1. users
   * Records: 500
   * Period: Jan 2018 - Dec 2018
   * Variables:
     * user_id
     * first_name
     * last_name
     * age
     * reg_date
     * churn_date
     * city
     * plan
2. calls
   * Records: +137 000
   * Period: Jan 2018 - Dec 2018
   * Variables:
     * id
     * call_date
     * duration
     * user_id
3. messages
   * Records: +76 000
   * Period: Jan 2018 - Dec 2018
   * Variables:
     * id
     * message_date
     * user_id
4. internet
   * Records: +104 000
   * Period: Jan 2018 - Dec 2018
   * Variables:
     * id
     * mb_used
     * session_date
     * user_id
5. plans
   * Variables:
     * plan_name
     * usd_monthly_fee
     * minutes_included
     * messages_included
     * mb_per_month_included
     * usd_per_minute
     * usd_per_gb
## 🔬 Methodology

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Hypotesis test

## 💡 Results and Key Insights

- Ultimate plan yields more income.
- Users from the NY-NJ area generate less profit that the rest.
## 🛠️ Tools and Technologies

- Python: pandas, seaborn, scipy

