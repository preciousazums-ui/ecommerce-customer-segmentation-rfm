# ecommerce-customer-segmentation-rfm
## 📌 Project Overview
This project applies **Recency, Frequency, and Monetary (RFM)** modeling techniques to segment e-commerce customers based on their purchasing behavior. By identifying high-value customers, churn risks, and casual shoppers, business teams can design targeted marketing strategies.

## 🛠️ Tools & Technologies Used
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Methodology:** RFM Scoring & Clustering (K-Means)

## 📊 Key Highlights & Segmentation Breakdown
1. **Data Preprocessing:** Cleaned transactional data, calculated purchasing recency, total order frequency, and aggregate spending per customer.
2. **RFM Scoring:** Assigned scores (1–5) to rank customer value across all three dimensions.
3. **Actionable Business Insights:**
   - **Champions/Loyal Customers:** High frequency and spend — targeted for loyalty rewards.
   - **At-Risk Customers:** High monetary value but low recency — targeted for win-back email campaigns.
   - **New/Occasional Shoppers:** High recency but low frequency — targeted for onboarding discounts.

## 📁 Repository Structure
- `notebooks/` - Complete RFM calculation and customer clustering notebook.
- `data/` - Sample e-commerce transactional dataset.
