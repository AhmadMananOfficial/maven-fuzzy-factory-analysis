# E-commerce Sales Growth Analysis

## Background

Maven Fuzzy Factory is an e-commerce company that sells stuffed animal products directly to customers through its website. As a Data Analyst at the company, I was tasked with analyzing the company's data **March 2012 to March 2015** to understand its overall business performance and identify opportunities for growth. My goal was to answer key business questions around 
* **Where customers come from?**
* **Which channels and products perform best?** 
* **How the business has grown over time?** 
* **Where customers drop off during their journey?**. 

The insights from this analysis are intended to support data-driven decisions on **marketing investment, website optimization, and future business growth**.

<img width="900" height="500" alt="Screenshot 2026-08-24 152731" src="https://github.com/user-attachments/assets/51c149f5-24b6-4895-bb5c-e612842db7c3" />

---

# Executive Summary

The business grew strongly from 2012 to 2015, with monthly sessions increasing from **1,879 to 23,778** and orders  from **60 to 2,067**. Growth was not driven by traffic alone: conversion rate nearly tripled from **3.2% to 8.7%**, while net profit per session increased from **$0.9 to $3.3**.

**Search was the main acquisition engine**, with Google Non-Brand generating **59.8% of total sessions** and the highest overall volume of orders and profit. Brand campaigns brought less traffic but its conversion rate is awesome, with Bing Brand reaching an **8.9% conversion rate**, showing the value of high-intent customers.

The biggest opportunity is **mobile conversion**. Mobile generated **30.8% of sessions but only 14.0% of orders**, converting at just **3.1% compared with 8.5% on desktop**. Funnel analysis showed that mobile users underperformed at every stage of the purchase journey, pointing to a broader mobile experience issue rather than a single checkout problem.

The product portfolio also expanded from **one product in 2012 to four products by late 2014**, creating additional revenue streams and reducing reliance on Mr. Fuzzy. Meanwhile, the Social Pilot campaign was the weakest major campaign, generating only **$0.4 net profit per session**, compared with **$2.3 for Google Non-Brand**.

**Overall, the business has built a strong engine for attracting and converting customers. The next stage of growth should focus on converting existing traffic more effectively—especially on mobile—while continuing to invest in high-performing search channels, strengthening marketing attribution, and addressing underperforming campaigns.**

---

# Insights Deep Dive

## 1. Search Is the Main Customer Acquisition Engine.

### 📈 Growth Since Launch (Mar 2012 → Feb 2015)

| Metric | Then → Now | Growth |
|---|---|:---:|
| **Monthly Sessions** | 1,879 → 23,778 |  **12.7x** |
| **Monthly Orders** | 60 → 2,067 |  **34.5x** |
| **Conversion rate** | 3.2% → 8.7% |  **+5.5 pts** |
| **Profit/session** | $0.90 → $3.30 |  **3.7x** |

The business is heavily driven by search, especially Google. Google Non-Brand alone brings almost 60% of all our website traffic and generates the largest share of our orders and profit. So, there is no question about where most of our growth is coming from—search is our biggest customer acquisition engine.

But there is an interesting difference between bringing in more people and bringing in the right people.

Our Brand campaigns bring less traffic, but the people who arrive through them are much more likely to buy. For example, Bing Brand has the highest conversion rate at 8.9%. This tells us something important: people who already know the brand come to the website with stronger buying intent. In simple terms, Non-Brand campaigns give us scale, while Brand campaigns bring us higher-quality traffic.


<img width="1314" height="629" alt="Screenshot 2026-08-25 121945" src="https://github.com/user-attachments/assets/05ed4dcb-6050-4c56-a3b6-bbcef8f9bce4" />

---

## 2. Mobile Is the Biggest Conversion Opportunity

At first, mobile traffic looked healthy. About 31% of our visitors come from mobile. But when we followed those visitors through the customer journey, a different picture emerged. Mobile generates 31% of our traffic but only 14% of our orders, with conversion rate of 3.1%. This is very low when we compared it with desktop conversion rate of 8.5%. That is a big gap.

| Metric           |   Mobile |  Desktop |
| ---------------- | -------: | -------: |
| Share of Traffic |      31% |      69% |
| Conversion Rate  | **3.1%** | **8.5%** |
| Share of Orders  |      14% |      86% |

And the problem is not limited to one campaign or one traffic source. We see the same pattern with Google, Bing, Brand, and Non-Brand traffic. Mobile visitors consistently drop off more than desktop visitors throughout the journey, from viewing products, to adding items to the cart, to completing checkout.

<img width="992" height="653" alt="Screenshot 2026-08-25 124554" src="https://github.com/user-attachments/assets/01c64138-5b07-469e-8888-a9a002d8234a" />

So the real question is probably not, **How do we get more mobile visitors?** We already have them. The better question is:

> **Why are so many of them leaving without buying?**

This is where I would focus next. Improving the mobile page and checkout experience could be one of our biggest growth opportunities because we already have a large number of potential customers visiting from mobile every day. Even a small improvement in mobile conversion could create a meaningful increase in orders without needing to spend more to acquire additional traffic.

---

## 3. The Social Pilot Campaign Needs Attention

There is also one area that clearly needs attention: the Social Pilot campaign. It brings visitors, but very few of them become customers, especially on mobile. Before putting more money into that campaign, I would review whether we are targeting the right audience and whether the ad message matches what customers see when they arrive on the website.

| Metric           |   Social Pilot |  Google Non-Brand | Bing Non-Brand |
| ---------------- | -------: | -------: | ------: |
| Conversion Rate |      1.1% |      6.7% | 7.0% |
| Revenue generation  | $3,597 | $1,074,110 | $215,859 |
| Net profit per session  |      $0.4 |      $2.3 | $2.4 |

The campaign performs very poor but this does not automatically mean the campaign should be stopped. The next step should be to understand why its traffic is underperforming.Ask questions like:

* Is the campaign targeting the right audience?
* Does the advertisement match the landing page?
* Are mobile users receiving a poor experience?
* Is the campaign attracting visitors with low purchase intent?

---

## 4. Refund rate improved overall, with one anomaly that doesn't fit

The refund rate decreased from an average of approximately 6-7% in 2012 to consistently under 4% by 2015, marking a significant and sustained improvement. However, there were two notable exceptions: the refund rate spiked to 9.2% in August 2014 and 9.3% in September 2014, which were much higher than any other month that year. 

This spike does not align with the typical seasonal trends, as the refund rates in November and December have consistently remained under 4% each year. Therefore, it appears that this spike may have been an isolated issue—potentially due to a bad batch, shipping problems, or a promotion that attracted the wrong customers—rather than a seasonal effect.

<img width="1015" height="567" alt="Screenshot 2026-08-25 134404" src="https://github.com/user-attachments/assets/33281df7-8a70-4d37-a0f5-862dccce76f2" />

---

## 5. The Business Reduced Its Dependence on One Product

In the beginning, the business relied entirely on **Mr. Fuzzy** for revenue. Over time, the company expanded its portfolio by introducing Love Bear, Sugar Panda, and Mini Bear. Still Mr. Fuzzy remained the largest revenue driver, but the newer products gradually created additional sources of revenue. Diversification reduces dependence on a single product and creates more opportunities for customers to purchase different items.

<img width="1290" height="677" alt="Screenshot 2026-08-25 131832" src="https://github.com/user-attachments/assets/3458534e-2c0d-4c2a-b8e0-f06ca4b94394" />

---

# Recommendations

Based on the analysis, I would recommend the following actions.

## 1. Make Mobile Optimization the Top Priority
The business already receives a significant amount of mobile traffic, but the conversion rate is substantially below desktop. Focus on investigating and improving:

* Product page experience
* Add-to-cart process
* Mobile navigation
* Checkout forms
* Page loading speed
* Button visibility and usability

> **The biggest immediate opportunity is not necessarily getting more mobile visitors—it is converting more of the mobile visitors we already have.**

## 2. Continue Investing in High-Performing Search Channels

Google Non-Brand is the primary source of customer acquisition and should continue to be a major focus. At the same time, Brand campaigns should be protected because they bring highly qualified visitors with stronger purchase intent.

## 3. Investigate Social Pilot Before More Investment

The Social Pilot campaign currently produces weak returns compared with other channels. Before increasing investment, investigate:

* Audience targeting
* Ad messaging
* Landing-page relevance
* Device-specific performance

If the campaign cannot improve its conversion efficiency, budget may be better allocated to stronger-performing channels.

---

# Final Takeaway

> **We have already built a strong engine for bringing customers to the business; the next stage of growth is making sure more of those customers, especially mobile users actually complete the journey and buy.**
