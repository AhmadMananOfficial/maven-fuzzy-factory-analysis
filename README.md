# E-commerce Sales Growth Analysis

## Background

Maven Fuzzy Factory is an e-commerce business selling stuffed animal products through its website. The business wants to better understand its growth, customer acquisition, website performance, product portfolio, and opportunities to improve conversions.

For this project, I analyzed website sessions, pageviews, orders, products, order items, and refunds using SQL. The goal was not simply to report numbers, but to answer important business questions:

* How has the business grown over time?
* Which marketing channels bring the most valuable customers?
* Which campaigns perform well and which need attention?
* How do desktop and mobile customers behave differently?
* Where are customers dropping off in the purchase journey?
* How has the product portfolio contributed to growth?

The analysis covers the period from **March 2012 to March 2015** and focuses on turning raw e-commerce data into actionable business insights.

---

# Executive Summary

The business has experienced strong growth between 2012 and 2015. However, the most important finding is that growth has not come simply from attracting more visitors.

Over time, the business became better at converting visitors into customers, generating more value from each website session, and expanding from a single-product business into a broader product portfolio.

**Search is the main engine driving customer acquisition**, with Google Non-Brand generating the largest volume of traffic, orders, and profit. Brand campaigns, while smaller in volume, attract higher-intent visitors who are more likely to convert.

The biggest opportunity identified in the analysis is the **mobile experience**. Mobile accounts for approximately **31% of website traffic but only 14% of orders**. Desktop visitors convert at **8.5%**, compared with only **3.1% for mobile**. Further funnel analysis shows that mobile users underperform at every stage of the purchase journey.

The business is successfully bringing customers to the website. The next major opportunity is to improve how effectively those visitors—particularly mobile users—are converted into customers.

### Key Findings

* 📈 The business grew significantly in both traffic and orders over time.
* 🎯 Conversion improved from approximately **3% in the early period to nearly 9% at its peak**.
* 💰 Net profit per session increased from around **$0.9 to more than $3**.
* 🔍 Google Non-Brand is the largest customer acquisition channel, generating approximately **60% of total sessions**.
* ⭐ Brand campaigns generate higher conversion rates, indicating stronger customer intent.
* 📱 Mobile generates approximately **31% of traffic but only 14% of orders**.
* 💻 Desktop converts at **8.5%**, compared with **3.1% on mobile**.
* 🛒 Mobile users drop off more than desktop users throughout the entire purchase journey.
* 🧸 The business expanded from relying on one main product to generating revenue from multiple products.
* ⚠️ The Social Pilot campaign generates low-value traffic and should be reviewed before further investment.

---

# Insights Deep Dive

## 1. The Business Has Grown in Both Size and Efficiency

The business showed a strong upward trend over the analysis period.

In **March 2012**, the website generated:

* **1,879 sessions**
* **60 orders**
* **3.2% conversion rate**
* **$0.9 net profit per session**

By **February 2015**, performance had improved to:

* **23,778 sessions**
* **2,067 orders**
* **8.7% conversion rate**
* **$3.3 net profit per session**

This shows that the company did not grow simply by attracting more visitors.

> **As traffic increased, the business also became better at converting visitors and generating more value from each website session.**

---

## 2. Search Is the Main Customer Acquisition Engine

Google Non-Brand is the largest source of website traffic, accounting for approximately **60% of all sessions**.

It also generates the highest number of:

* Orders
* Revenue
* Net profit

This makes Google Non-Brand the business's primary channel for acquiring new customers at scale.

The analysis of previously untracked traffic also showed that a significant portion of it was associated with Google and Bing referrals, reinforcing the importance of search to the overall business.

> **Search is doing most of the heavy lifting when it comes to bringing potential customers to the website.**
---

## 3. Non-Brand Drives Scale, While Brand Traffic Drives Efficiency

Not all traffic is equally valuable.

Google Non-Brand delivers the largest volume of visitors and contributes the most total orders and profit. However, Brand campaigns generally have stronger conversion rates and higher profit per visitor.

For example, customers arriving through Brand campaigns already have some awareness of the business or product. As a result, they show stronger purchase intent.

This creates an important balance:

> **Non-Brand search helps the business reach new customers at scale, while Brand traffic brings visitors who are more likely to buy.**

The business should therefore evaluate marketing performance using both **volume and efficiency**, rather than focusing only on traffic.

---

## 4. Mobile Is the Biggest Conversion Opportunity

This is the most important finding from the analysis.

Mobile accounts for approximately **31% of total website traffic**, which means the business is successfully attracting a significant number of mobile visitors.

However, mobile generates only around **14% of total orders**.

| Metric           |   Mobile |  Desktop |
| ---------------- | -------: | -------: |
| Share of Traffic |      31% |      69% |
| Conversion Rate  | **3.1%** | **8.5%** |
| Share of Orders  |      14% |      86% |

Desktop visitors are nearly **three times more likely to convert** than mobile visitors.

The key insight is:

> **The business does not have a mobile traffic problem. It has a mobile conversion problem.**

This means acquiring additional mobile traffic may not be the most effective immediate growth strategy. There is already a large audience visiting from mobile—the opportunity is to help more of them complete a purchase.

---

## 5. Mobile Users Drop Off Throughout the Entire Purchase Journey

To understand why mobile conversion is lower, the customer journey was analyzed from product browsing to completed orders.

| Funnel Stage     |   Mobile |  Desktop |
| ---------------- | -------: | -------: |
| Reached Product  |    47.2% |    58.8% |
| Reached Cart     |    13.6% |    23.0% |
| Reached Shipping |     8.1% |    16.1% |
| Reached Billing  |     5.7% |    13.4% |
| Placed Order     | **3.1%** | **8.5%** |

Mobile performs worse than desktop at every stage.

This is important because it suggests that the issue may not be one isolated problem.

> **The data points toward a broader mobile experience issue rather than a single broken step in the checkout process.**

The highest-priority areas for further investigation are:

* Product page usability
* Add-to-cart experience
* Cart navigation
* Checkout form complexity
* Mobile page speed
* Button visibility
* Mobile-specific technical issues
* Unexpected costs appearing during checkout

---

## 6. The Social Pilot Campaign Needs Attention

The Social Pilot campaign brings visitors to the website, but its performance is weak compared with other major campaigns.

It has particularly low:

* Conversion
* Revenue generation
* Net profit per session

The campaign performs especially poorly on mobile.

This does not automatically mean the campaign should be stopped. The next step should be to understand why its traffic is underperforming.

Possible questions include:

* Is the campaign targeting the right audience?
* Does the advertisement match the landing page?
* Are mobile users receiving a poor experience?
* Is the campaign attracting visitors with low purchase intent?

> **Before increasing investment, the business should investigate why Social Pilot traffic is failing to convert.**

---

## 7. The Business Reduced Its Dependence on One Product

In the beginning, the business relied entirely on **Mr. Fuzzy** for revenue.

Over time, the company expanded its portfolio by introducing:

* **Love Bear**
* **Sugar Panda**
* **Mini Bear**

Mr. Fuzzy remained the largest revenue driver, but the newer products gradually created additional sources of revenue.

This represents an important change in the business model:

> **The company evolved from a one-product business into a more diversified product portfolio.**

Diversification reduces dependence on a single product and creates more opportunities for customers to purchase different items.

---

# Recommendations

Based on the analysis, I would recommend the following actions.

## 1. Make Mobile Optimization the Top Priority

The business already receives a significant amount of mobile traffic, but the conversion rate is substantially below desktop.

Focus on investigating and improving:

* Product page experience
* Add-to-cart process
* Mobile navigation
* Checkout forms
* Page loading speed
* Button visibility and usability

> **The biggest immediate opportunity is not necessarily getting more mobile visitors—it is converting more of the mobile visitors we already have.**

---

## 2. Continue Investing in High-Performing Search Channels

Google Non-Brand is the primary source of customer acquisition and should continue to be a major focus.

At the same time, Brand campaigns should be protected because they bring highly qualified visitors with stronger purchase intent.

The strategy should balance:

**Scale → Non-Brand Search**

with

**Efficiency → Brand Search**

---

## 3. Investigate Social Pilot Before Scaling

The Social Pilot campaign currently produces weak returns compared with other channels.

Before increasing investment, investigate:

* Audience targeting
* Ad messaging
* Landing-page relevance
* Device-specific performance

If the campaign cannot improve its conversion efficiency, budget may be better allocated to stronger-performing channels.

---

## 4. Continue Expanding and Evaluating the Product Portfolio

The product portfolio has helped reduce the business's dependence on Mr. Fuzzy.

Future product decisions should continue to evaluate:

* Revenue contribution
* Profitability
* Product adoption after launch
* Cross-selling opportunities

Mr. Fuzzy remains the core product, but additional products provide important opportunities for future growth.

---

## 5. Improve Marketing Attribution

A significant amount of traffic was initially classified as Unknown because UTM information was missing.

Improving campaign tagging would allow the business to:

* Better measure marketing performance
* Identify true traffic sources
* Allocate budget more accurately
* Make stronger decisions about campaign investment

> **Better tracking leads to better marketing decisions.**

---

# Final Takeaway

> **The business has built a strong engine for growth. Search is bringing customers to the website, conversion has improved over time, and the product portfolio has expanded beyond a single product. The biggest opportunity now is to get more value from the traffic the business already has—especially by improving the mobile customer experience.**
