# product-data-cleaning-missing-duplicates
## 📌 Background Problem
Real-world data is often messy and incomplete, and this dataset is no exception. The dataset contains product information from multiple beauty brands, such as product names, categories, ratings, and launch dates. However, several challenges were identified:
- Presence of **missing values** in key columns such as `active_date`, `average_rating_by_types`, and `categories`
- A column (`price_by_combinations`) with too many null values to be useful
- The need to ensure the dataset has **no duplicate entries** before further analysis

## 🧪 Libraries Used
This project was completed using the following libraries
- pandas==2.2.2
- numpy==1.25.2

## Insights
🔍 `price_by_combinations` was dropped because it had over 99% missing data.
🧩 Columns like `active_date`, `categories`, and `average_rating_by_types` had manageable missing values and were filled using the **mode**.
📌 The `rating_types_str` column was filled with `"Unknown"` for consistency in categorical data.
🔄 Duplicate check showed **no duplicate records** were present.
✅ After cleaning, the dataset is now **complete and consistent**, ready for exploratory data analysis (EDA) and further modeling.

## Advice
- Continue with Exploratory Data Analysis (EDA)
- Use Visualization
- Automate the cleaning workflow
- Enrich the dataset
- Review Imputation Strategies

#Datacleaning #EDA #Python 
You’re welcome to connect with me if you'd like to discuss this further, Jessicaagnesiat@gmail.com
