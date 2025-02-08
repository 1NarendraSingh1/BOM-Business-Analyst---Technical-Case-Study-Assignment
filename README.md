# 1. Excel Task
# Task 1. Channel Performance Analysis

- Total orders per channel.
- Average Order Value (AOV).
- Revenue contribution per channel.
- Profitability by product subclass.

- Total orders and total sales are available by channel.
- Average Order Value (AOV) and revenue contribution are calculated.
# Visialization by Ordertype & Gender

![image](https://github.com/user-attachments/assets/726dc3c2-6cba-496e-81ae-9d3fc5a97d9c)


# Visualization: Sales & Profits by Channels

![image](https://github.com/user-attachments/assets/a694e0b4-d25d-4c54-bc3b-922737e55d6b)


# Channel Performance and Profitability Analysis

**1.** **Top-Performing Channels (Based on Sales Revenue)**

- BEWAKOOF leads with ₹3,078,073.71 in sales (23.1% of total revenue).
- MYNTRA and its subcategories contribute significantly, with a total of over ₹6.84 million, making it the strongest marketplace collectively.
  
**2.** **Underperforming Channels (Low Sales and Orders)**

- SNAPDEAL_BK_BLR_SHR and POP_BK_PROZO_BHIWANDI have the lowest sales, with ₹36,722.50 and ₹49,732.00, respectively.
- Their low order volume and revenue share (<1%) indicate that they need either better marketing or pricing strategies.

**3.**  **Highest and Lowest AOV (Average Order Value)**

- NYKAA_FASHION_BK_KOL_SHR has the highest AOV at ₹962.81, indicating premium product sales.
- SNAPDEAL_BK_BLR_SHR and POP_BK_PROZO_BHIWANDI have the lowest AOV (~₹420-₹456), showing a focus on budget-friendly products.

**4.** **Profitability Insights**

**Highest Profit Margin (%)**

- Bewkoof channel has overall 23% profit margin highest among all.
- MYNTRA channels have profit margins exceeding 11%, making them highly profitable.
- NYKAA_FASHION_BK_PROZO_BHIWANDI has a 6.7% profit margin, making it a strong channel for premium products.
  
**Lowest Profit Margin (%)**

- SNAPDEAL_BK_BLR_SHR and POP_BK_PROZO_BHIWANDI have profit margins of ~0.2%-0.3%, making them barely profitable.
- FLIPKART and FLIPKART_BK_BLR_SHR also show weak profit margins (~2%).

# Suggestions for Optimization

**1.** **Expand Focus on High-Profit Channels:**

- Invest in Myntra and Bewakoof, which contribute over 35% of total revenue and have strong profit margins.
- Explore higher-margin product listings on NYKAA Fashion, especially in the premium segment.

**2.** **Improve Low-Performing Channels:**

- Consider discounted bundles or marketing efforts for Snapdeal and POP to increase order volumes.
- Reassess pricing strategy on Flipkart, as its low profit margin (2-3%) might not justify the platform fees.
- Optimize Pricing for Underperforming Channels:

**3.** **Increase prices on Snapdeal and POP while maintaining competitive positioning.**

**4.** **Adjust cost structures or promotional strategies for Flipkart channels to increase profitability.**


# 2.  Python Task
# BOM-Business-Analyst-Technical-Case-Study-Assignment
BOM(Bill of Materials) Business Analyst Case Study Solution using Python, Pandas manipulation and Visualization Technique
# Python-Based Tasks
**Customer Acquisition vs Retention**

- Objective: Assess how different marketplaces perform in acquiring and retaining customers.
- Key Metrics:
- Total orders.
- Unique customers.
- Repeat orders (Repeat Orders = Total Orders - Unique Customers).
- Retention rate (% of repeat orders among total orders).
  
**Deliverables:**

- A summary of retention metrics by channel.
- Observations on which marketplaces drive customer loyalty and suggestions to improve retention.

**Marketplace Efficiency: COD vs Prepaid Orders**

- Objective: Compare the operational and financial efficiency of order types (COD vs Prepaid) across marketplaces.
- Key Metrics:
- Total sales.
- Total profit.
- Average profit margin by channel and order type.
  
**Deliverables:**
- A detailed breakdown of these metrics by channel and order type.
- Observations on payment method efficiency and strategies to optimize COD or incentivize prepaid adoption.


  # **Customer Acquisition vs. Retention**
  
- Bewakoof has the highest repeat orders, but its retention rate is still low (~0.3%).
- Flipkart and other marketplace channels have no repeat customers in this dataset, meaning all customers are unique.

  ![image](https://github.com/user-attachments/assets/b06e0280-dbf6-45c2-a66d-41bf45b9452d)


**Observations**

- The low retention rate suggests that customers are not returning for repeat purchases.
 **Suggestions:**
  
**1. Gamification & Loyalty Programs**

- Introduce tier-based rewards (Silver, Gold, Platinum) based on repeat purchases.
- Offer "Spin & Win" discounts or reward points for every purchase to encourage repeat buying.
- Implement a streak-based discount (e.g., 10% off if a customer orders again within 30 days).

**2. Exclusive "VIP Retention Offers"**

- Provide "Early Access" to new product launches for repeat customers.
- Offer exclusive discounts to customers who have placed multiple orders in the past 3 months.

**3. Subscription Model for Repeat Buyers**

- Offer a subscription service for products frequently ordered (e.g., fashion, cosmetics, or essentials).
- Provide a 10-15% discount for subscribing to recurring purchases.

# **Marketplace Efficiency (COD vs. Prepaid Orders)**
- COD orders tend to have a slightly higher average profit margin than prepaid orders.
- Bewakoof COD orders have a 52.1% profit margin, while Prepaid is slightly lower at 48.2%.
- Flipkart and other channels also show similar trends where COD is slightly more profitable.

![image](https://github.com/user-attachments/assets/266f9082-1d33-4034-a2a7-c2c1643a5d73)


**Observations**

- Since COD is more profitable, marketplaces should optimize logistics to reduce COD-related risks (e.g., non-deliveries).
- 
**Suggestions:**
  
**1. Instant Prepaid Discounts on COD Checkouts**

- When a customer selects COD, show them a popup:
- "Pay Online & Get ₹50 Cashback Instantly!"
- "Prepay & Unlock Free Express Delivery!"

**2. Hybrid COD-Prepaid Model**

- Allow customers to pay a small advance online and the remaining amount on delivery.
- Example: "Pay ₹100 now & the rest on delivery"—this builds trust while reducing COD risks.

**3. Gamify Prepaid Payments with Rewards**

- Every prepaid order enters the customer into a lucky draw for a big reward.
- Example: "Prepay & Get a Chance to Win a Free Gift Every Month!"
