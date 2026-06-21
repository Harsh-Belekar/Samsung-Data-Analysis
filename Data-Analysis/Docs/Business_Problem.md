# 🏢 SAMSUNG DATA ANALYSIS - BUSINESS PROBLEM STATEMENT

---

## 🎯 EXECUTIVE SUMMARY

Samsung, one of the country's largest consumer electronics companies, operates across 50+ cities with over 10,000 dealer and retail partners. Despite generating ₹3,200+ Crores in gross revenue over the past 4 years (2022–2025), the company faces critical challenges in optimising sales channel performance, improving customer retention, managing after-sales service quality, and maintaining healthy inventory levels across its national supply chain.

This comprehensive data analysis project aims to uncover actionable insights from 750,000+ sales transactions and 2,000,000+ business events to drive strategic decision-making across Sales, Marketing, After-Sales, Supply Chain, and Finance.

---

## 📋 BACKGROUND

### Company Overview

Samsung India is a consumer electronics manufacturer and retailer that sells products across six major categories:
•	Smartphones (Galaxy S, A, M, Z Series)
•	Tablets (Galaxy Tab S and Tab A Series)
•	Televisions (Crystal 4K, QLED, Neo QLED)
•	Air Conditioners (Wind-Free, Digital Inverter)
•	Washing Machines (Front Load, Top Load)
•	Refrigerators (Single Door, Double Door, French Door)

**Samsung India generates revenue through:**
•	Direct product sales via `Samsung.com` and Samsung SmartCafé outlets
•	Partner channel sales through Flipkart, Amazon IN, Croma, Reliance Digital, and Vijay Sales
•	EMI and financing partnerships with HDFC Bank, Bajaj Finserv, and SBI Card
•	After-sales service charges at 1,200 authorised service centres

**Current Situation**

Over the past 4 years, Samsung India has:
•	Served 200,000+ registered customers across Premium, Mid-Range, Budget, and Enterprise segments
•	Partnered with 10,000+ dealers and retail outlets across 50+ cities
•	Processed 750,000+ sales transactions
•	Generated ₹3,200+ Crores in gross revenue
•	Maintained operations across 25 warehouses covering all major Indian states
•	Handled 200,000+ after-sales complaints through 1,200 service centres
•	Processed 77,000+ product returns across all channels

Despite this scale, several critical challenges have emerged that require data-driven solutions.

---

## 🔴 KEY BUSINESS CHALLENGES


### 1. REVENUE PERFORMANCE & CHANNEL OPTIMIZATION

**Problem:**
•	Revenue growth is uneven across channels — online platforms drive volume but offline stores drive higher average order values
•	The impact of Diwali, IPL Season, Republic Day, and Independence Day sales on revenue is tracked anecdotally but never quantified
•	No clear understanding of which product-channel-region combination delivers the highest return
•	Effective discount (gap between MRP and actual selling price) is not monitored systematically
•	Transaction failure and cancellation rates are consuming potential revenue silently

**Questions to Answer:**
•	What is our total revenue by year, quarter, and financial year (April–March)?
•	Which 3 product categories contribute 80% of total revenue (Pareto analysis)?
•	Which sales channel — `Samsung.com`, Flipkart, Amazon IN, or Croma — delivers the highest average order value?
•	What is the revenue premium during festive seasons (October–December) versus non-festive months?
•	Which 5 states generate the highest revenue and what is their year-over-year growth rate?
•	What is the effective discount percentage by product category?
•	What is our transaction completion rate — and how much revenue is being lost to failed and cancelled orders?

---

### 2. CUSTOMER RETENTION & LOYALTY

**Problem:**
•	Samsung India cannot identify which customers are at risk of switching to Apple, OnePlus, or Xiaomi until it is too late
•	Customer Lifetime Value (LTV) is not calculated or tracked at the individual or segment level
•	High-value customers are not being treated differently from low-value customers in marketing or retention efforts
•	No visibility into repeat purchase rates — Samsung India does not know how many customers buy again after their first purchase
•	RFM segmentation (Recency, Frequency, Monetary) has never been applied to the customer base

**Questions to Answer:**
•	What is our customer retention rate and repeat purchase rate by segment?
•	Who are our most valuable customers by Lifetime Value?
•	How can we identify customers at risk of churning (no purchase in 12+ months)?
•	What is the RFM segment distribution — how many Champions, Loyal, At-Risk, and Lost customers do we have?
•	Which customer segments — Premium, Mid-Range, Budget, or Enterprise — have the highest LTV?
•	Which age bands (Teen, Young Adult, Adult, Middle-Aged, Senior) spend the most per order?
•	What drives repeat purchases — product category, payment mode, or channel?

---

### 3. PRODUCT PORTFOLIO PERFORMANCE

**Problem:**
•	Significant revenue variance exists across product categories but the root cause is unknown
•	Smartphone categories dominate sales but appliance categories (ACs, Washing Machines, Refrigerators) performance is not benchmarked
•	No systematic approach to identifying which products are underperforming relative to their MRP potential
•	Price band analysis (Budget / Mid-Range / Premium / Ultra-Premium) has never been done across categories
•	The relationship between product ratings, complaint rates, and return rates is not understood

**Questions to Answer:**
•	Which product categories and subcategories generate the most revenue and units sold?
•	What is the revenue contribution of each price band — Budget (<₹20K), Mid-Range (₹20K–₹50K), Premium (₹50K–₹1L), Ultra-Premium (>₹1L)?
•	Which product has the highest return rate as a percentage of units sold?
•	Which products have the highest complaint rate — and is it correlated with low average ratings?
•	What is the average customer rating by product category?
•	Which products are underperforming their MRP (high discount, low volume)?
•	Which new product launches (by launch date) achieved the fastest sales ramp-up?

---

### 4. AFTER-SALES SERVICE QUALITY & CSAT

**Problem:**
•	Samsung India operates 1,200 service centres but has no unified view of which centres are performing well and which are damaging brand trust
•	A complaint that takes 15 days to resolve with a CSAT of 2 is not just an operational failure — it is a future sale lost
•	The national average CSAT score and resolution rate are unknown at the leadership level
•	Escalation rate (complaints that escalate beyond first-level resolution) is not tracked
•	No correlation analysis has been done between CSAT scores and future customer purchase behaviour

**Questions to Answer:**
•	What is the national complaint resolution rate and average CSAT score (1–5)?
•	Which 5 service centres have the lowest CSAT scores and need immediate intervention?
•	What are the most common issue types — Screen Damage, Battery Drain, Charging Problems — and which products generate each issue most frequently?
•	What is the average resolution time by issue type and by priority (Urgent, High, Medium, Low)?
•	What percentage of complaints are escalated — and what drives escalation?
•	Is there a correlation between CSAT score and repeat purchase probability?
•	Which states have the highest complaint rates relative to their sales volume?

---

### 5. RETURN RATE & REFUND OPTIMISATION

**Problem:**
•	Samsung India processes 77,000+ product returns but has no structured view of the root causes
•	A cluster of returns citing "Manufacturing Defect" on a specific product SKU is a quality signal that is buried in unstructured data
•	Channels with high return rates may indicate misleading product listings — but this has never been investigated
•	The total financial impact of returns (refund value + reverse logistics + replacement cost) is not reconciled against gross revenue
•	No identification of high-risk product SKUs that should trigger a quality audit

**Questions to Answer:**
•	What is the overall return rate — and how does it vary by product category and by channel?
•	What are the top 5 return reasons — and do they vary by product type or channel?
•	Which products have a return rate above 10% that should trigger a quality investigation?
•	How much total revenue is lost to refunds per month — and what is the net revenue after returns?
•	Which channels (Flipkart, Amazon, Croma, etc.) have disproportionately high return rates?
•	What is the split between refunds and replacements — and does it vary by product category?
•	What condition are returned products typically in (Good, Fair, Damaged, Sealed)?

---

### 6. SUPPLY CHAIN & INVENTORY MANAGEMENT

**Problem:**
•	Samsung India has no real-time visibility into which products are at risk of stockout across its 25 warehouses
•	Slow-moving products occupy expensive warehouse space while fast-moving products go out of stock — causing invisible lost revenue
•	Stock velocity (daily sales rate) is not compared against stock levels to predict stockouts before they happen
•	Warehouse capacity utilisation is unmonitored — some facilities may be overcrowded while nearby warehouses are underutilised
•	The financial value of inventory at risk of stockout is unknown to the supply chain leadership team

**Questions to Answer:**
•	How many products are currently at or below their reorder level across all 25 warehouses?
•	Which warehouse has the highest concentration of critical-stock products?
•	What is the estimated days-of-stock for Samsung India's top 20 best-selling products?
•	What is the total financial value (MRP × deficit units) of inventory at risk of stockout?
•	Which warehouses are over-capacity versus under-utilised?
•	How frequently are products being restocked — and is the restocking frequency aligned with sales velocity?
•	Which product categories are most vulnerable to stockout events during festive seasons?

---

### 7. FINANCIAL ANALYTICS & PAYMENT INTELLIGENCE

**Problem:**
•	Samsung India collects payments across 7 modes — UPI, Credit Card, Debit Card, Net Banking, EMI, Cash on Delivery, and Wallet — each with a different cost structure and failure rate
•	Payment failure rates by mode are unknown — a high UPI failure rate and a high Credit Card failure rate have different causes and different fixes
•	EMI adoption for Premium and Ultra-Premium products has never been measured, despite EMI being the primary enabler of high-value purchases in India
•	GST reconciliation across 4 slabs (5%, 12%, 18%, 28%) is not automated
•	The strategic shift toward UPI has not been quantified or actioned

**Questions to Answer:**
•	What is the payment success rate, failure rate, and average transaction value for each payment mode?
•	Which banks have the highest payment failure rates — and for which payment modes?
•	What is the EMI adoption rate for Premium (₹50K–₹1L) and Ultra-Premium (>₹1L) products?
•	How much total GST was collected by slab — and how does it break down by product category?
•	What is the month-on-month trend of UPI adoption — is it growing at the expense of other modes?
•	What is the total net revenue after deducting refunds — and how does it trend month over month?
•	Which payment mode has the highest average order value — and what does this tell us about customer behaviour?

---

## 🎯 PROJECT OBJECTIVES

### Primary Objectives

**1. Develop Customer Segmentation & Retention Strategy**
- Apply RFM (Recency, Frequency, Monetary) analysis to all 200,000 customers
- Classify customers into Champions, Loyal, Potential, At-Risk, and Lost segments
- Calculate Customer Lifetime Value (LTV) by segment and city
- Identify churn risk customers and develop targeted re-engagement strategies

**2. Optimise Revenue & Channel Performance**
- Identify the top revenue-driving product-channel-region combinations
- Quantify the festive season revenue premium and create a seasonal marketing calendar
- Measure the effective discount by category and develop pricing recommendations
- Maximise transaction completion rate by reducing payment failures and cancellations

**3. Improve After-Sales Service Quality**
- Establish national benchmarks for CSAT, resolution rate, and resolution time
- Identify and prioritise the bottom-performing service centres for intervention
- Correlate CSAT scores with customer retention to build the business case for service investment
- Reduce average resolution days across all complaint priorities

**4. Reduce Return Rate & Protect Revenue**
- Identify high-risk product SKUs with return rates above 10%
- Quantify the total financial impact of returns on net revenue
- Investigate channel-specific return patterns for listing or fulfilment issues
- Develop return rate reduction recommendations by product category

**5. Strengthen Supply Chain Resilience**
- Build a real-time inventory health monitor covering all 25 warehouses
- Identify stockout risks before they impact sales — especially before festive seasons
- Calculate days-of-stock per product using sales velocity from transaction data
- Recommend optimal reorder levels based on historical demand patterns

**6. Drive Data-Backed Financial Decisions**
- Automate GST reconciliation across all 4 slabs using transaction data
- Identify the highest-value payment mode combinations for targeted promotion
- Build the business case for EMI promotion in Tier 2 cities for Premium products
- Track net revenue (gross revenue minus refunds) as the primary financial KPI

---

## 📊 EXPECTED DELIVERABLES

### 1. Analytical Deliverables

#### Customer Analysis Report
- RFM segmentation — Champions, Loyal, Potential, At-Risk, Lost
- Customer Lifetime Value analysis by segment and state
- Churn risk identification and prevention strategy
- Age band and gender behaviour patterns

#### Revenue & Product Performance Report
- Revenue trends by year, quarter, and financial year
- Top revenue-driving product categories and channels
- Festive season vs non-festive revenue comparison
- MRP vs actual selling price (effective discount) analysis

#### After-Sales & Complaint Analysis Report
- National CSAT score and resolution rate benchmarks
- Top and bottom performing service centres by CSAT
- Issue type frequency and product complaint rate matrix
- Escalation rate trends and root cause identification

#### Returns & Refund Analysis Report
- Return rate by product category, channel, and return reason
- High-risk product SKU identification (return rate > 10%)
- Financial impact — total refunds vs gross revenue by month
- Replacement vs refund split by category

#### Inventory & Supply Chain Report
- Stock health status across all 25 warehouses
- Products below reorder level with estimated days-of-stock
- Stockout risk financial value (MRP × deficit units)
- Warehouse capacity utilisation and restocking frequency

#### Financial & Payment Analysis Report
- Payment mode success rate, failure rate, and average order value
- GST collected by slab and by product category
- EMI adoption rate for Premium and Ultra-Premium products
- Net revenue trend — gross revenue minus total refunds

### 2. Visual Deliverables

#### Interactive Power BI Dashboard with:
- **Executive Summary page** — headline KPIs for CEO-level review
- **Revenue Performance page** — trends, channels, regions, and festive seasons
- **Customer Intelligence page** — RFM segments, LTV, churn risk map
- **After-Sales Health page** — CSAT, complaints, and service centre performance
- **Returns & Refunds page** — return rate, reasons, and financial impact
- **Inventory Monitor page** — stock health, reorder alerts, and warehouse map
- **Financial Analytics page** — payment modes, GST, EMI, and bank performance

### 3. Strategic Recommendations

#### Customer Retention Strategy
- Re-engagement campaign design for At-Risk and Lost segments
- Loyalty programme recommendations for Champions and Loyal segments
- Personalisation roadmap based on segment and channel preferences

#### Revenue Growth Strategy
- Channel investment recommendations based on AOV and completion rate
- Seasonal campaign calendar aligned with festive revenue premium data
- Pricing optimisation recommendations by product category and price band

#### After-Sales Excellence Roadmap
- Bottom 50 service centre intervention plan (training, capacity, SLA)
- Complaint reduction strategy by issue type and product category
- CSAT-to-retention correlation — building the business case for service investment

#### Supply Chain Resilience Plan
- Pre-festive season restocking checklist by product and warehouse
- Reorder level optimisation based on 90-day sales velocity
- Warehouse capacity rebalancing recommendations

---

## 🔍 ANALYTICAL APPROACH

### Data Analysis Methodology

#### 1.	Descriptive Analytics (What happened?)
- Revenue trend analysis — monthly, quarterly, and annual
- Product category and channel performance metrics
- Customer segment and demographic distribution
- Complaint and return volume tracking

#### 2.	Diagnostic Analytics (Why did it happen?)
- Root cause analysis of high return rates by product and channel
- Complaint escalation driver investigation
- Payment failure root cause by mode and bank
- Churn driver analysis for At-Risk customers

#### 3.	Predictive Analytics (What will happen?)
- Customer churn risk scoring (days since last purchase + purchase frequency)
- Inventory stockout prediction (days-of-stock vs reorder lead time)
- Festive season demand forecasting based on historical seasonal patterns
- Revenue forecasting by channel using trend extrapolation

#### 4.	Prescriptive Analytics (What should we do?)
- Targeted re-engagement recommendations for At-Risk customer segments
- Optimal reorder quantities for top 20 high-velocity products
- Service centre prioritisation for CSAT improvement investment
- EMI promotion targeting for Ultra-Premium products in Tier 2 cities

### Tools & Technologies

**Database**: PostgreSQL (Bronze → Silver → Gold pipeline)
**Analysis**: Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn)
**Visualization**: Power BI (DirectQuery on Gold schema)
**Documentation**: Jupyter Notebooks, Markdown
**Pipeline**: SQL (Bronze DDL, Silver Cleaning Views, Gold Star Schema Views)
