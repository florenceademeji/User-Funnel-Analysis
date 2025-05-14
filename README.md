📉 Customer-Funnel-Analysis

Customer Funnel Analysis is a crucial methodology used in product, marketing, and growth strategy to understand the journey a user takes from the first interaction with a digital product to the final conversion event — such as a purchase, signup, or checkout completion.

This process involves tracking and analyzing the various stages that potential users pass through, commonly referred to as “funnel stages.” In this project, the funnel includes:
	•	visit_landing
	•	view_product
	•	add_to_cart
	•	initiate_checkout
	•	purchase

The primary goal of funnel analysis is to identify where users drop off in their journey and understand the factors influencing their decisions at each stage. By examining conversion rates between stages, teams can identify friction points, optimize product flows, and enhance the overall user experience. This ultimately leads to better retention, higher conversion, and stronger revenue outcomes.

Project Overview

In this project, we simulate and analyze a user funnel using a synthetic dataset of 1,000 users. Each user moves through multiple funnel stages with probabilistic drop-offs, mimicking real-world behavior in e-commerce or SaaS environments.

The analysis includes:
	•	Generating a synthetic user funnel dataset with timestamps
	•	Tracking how many users reach each stage
	•	Calculating stage-by-stage conversion and drop-off rates
	•	Visualizing the funnel in a true funnel shape using Matplotlib
	•	Identifying the last stage reached by each user to pinpoint drop-off zones

Goals of the Analysis
	•	Visualize how users flow through each stage of the funnel
	•	Identify high-friction stages with significant user drop-off
	•	Calculate conversion efficiency at each point
	•	Provide actionable business insights to reduce churn and increase completions

Key Insights
	•	The largest user drop-off typically occurs between view_product and add_to_cart
	•	Funnel visualization clearly highlights bottlenecks
	•	Conversion rate progressively declines at each stage — pinpointing the weakest links helps improve targeting and UX

Tools Used
	•	Python
	•	Pandas
	•	NumPy
	•	Matplotlib
	•	Seaborn

Business Recommendations
	•	Simplify the add-to-cart experience to reduce friction
	•	Improve product page clarity with reviews, images, or value propositions
	•	Send cart reminders or offer small incentives for abandoned checkouts
