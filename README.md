Business Analysis Portfolio Project

Increase Sales for an E-commerce Company

Role: Business Analyst (simulated)
Industry: E-commerce / Retail
Goal: Identify why the company is losing customers and define requirements to increase sales by 20% within 6 months.


Part 1 — Problem Identification

Problem Statement:
The company has lost 20% of its customers over the last 6 months. Discount campaigns via email and SMS have not brought customers back. Sales are declining and the root cause is unknown.

As-Is (Current State):


Customer base has decreased by 20% in 6 months
Customers do not return despite receiving discount offers
Delivery time is perceived as too slow compared to competitors
The return process is complicated and discourages repeat purchases
Products do not always match their online descriptions, leading to dissatisfaction


Root Cause Analysis:

Root CauseImpactDelivery time too long (5–7 days)Customers choose faster competitorsProducts don't match descriptionsHigh return rate, loss of trustComplicated return processCustomers don't shop againGeneric, non-personalized offersLow open rate, low conversion

As-To-Be (Target State):


Delivery guaranteed within 3 business days
Product descriptions are accurate and include real photos
Returns are free on first purchase, with a return label included in the package
Customers receive personalized offers based on purchase history
20% increase in sales within 6 months



Part 2 — Stakeholders

StakeholderRoleInterestEnd CustomerBuyerFast delivery, accurate products, easy returnsCustomer Service ManagerInternalReduce complaints and return volumeWarehouse ManagerInternalRealistic delivery targets, logistics processMarketing ManagerInternalImprove campaign conversion ratesE-commerce Manager (Sponsor)Decision-maker20% sales increase in 6 monthsLogistics SupplierExternalDelivery agreements and SLA

Key Interview Questions:


What do you think is the main reason customers are not returning?
What would make the customer experience significantly better?
What does a realistic delivery timeline look like from a warehouse perspective?
What data do we have on why customers are returning products?



Part 3 — Requirements

Business Requirement (BR):


Increase sales by 20% within 6 months by improving delivery speed, product accuracy, and the return process.



Functional Requirements (FR):

IDRequirementFR-01The system shall send a personalized email or SMS within 2 days after purchase with relevant product recommendationsFR-02The system shall offer free returns on the first purchase and automatically include a return label in the order confirmationFR-03The system shall guarantee delivery within a maximum of 3 business daysFR-04All product pages shall display accurate descriptions and real product photosFR-05The system shall allow customers to track their order in real time

Non-Functional Requirements (NFR):

IDRequirementNFR-01Automated emails and SMS shall be sent within 2 seconds of the trigger eventNFR-02The platform shall maintain 99.9% uptimeNFR-03The return portal shall load within 2 seconds on mobile devices


Part 4 — User Stories

IDUser StoryPriorityUS-01As a customer, I want delivery within 3 days so that I can trust the company and choose it over competitorsHighUS-02As a customer, I want a simple return process so that I feel confident shopping againHighUS-03As a customer, I want personalized product offers so that I can discover items I actually likeMediumUS-04As a customer, I want to track my order in real time so that I know when my package will arriveMediumUS-05As a Customer Service Manager, I want to see return reasons logged automatically so that I can identify recurring product issuesMediumUS-06As an E-commerce Manager, I want a monthly report showing customer retention rate so that I can track progress toward the 20% sales goalHigh


Part 5 — Process Map

The process map below illustrates the current customer journey (As-Is) and the improved journey (As-To-Be) after the proposed changes.

📎 Process map created in Lucidchart — see image file in this repository.

As-Is flow: Customer visits site → browses → orders → waits 5–7 days → receives wrong/inaccurate product → tries to return → complicated process → does not return.

As-To-Be flow: Customer visits site → sees accurate product info → orders → receives within 3 days → easy return if needed → receives personalized follow-up offer → returns as a loyal customer.


Part 6 — Data Analysis (Excel)

The dataset used is a real Indian e-commerce sales dataset sourced from Kaggle.

Key findings from pivot table analysis:

Product CategoryNumber of OrdersKURTA3,704DRESS700Other categories< 300 each

Insights:


KURTA accounts for the large majority of all orders — this is the core product and should be the primary focus for quality improvements and marketing campaigns
DRESS is the second-largest category and should be included in personalized recommendation campaigns
Smaller categories have low volume and should not be prioritized in the initial improvement phase


Recommendation based on data: Focus product description improvements and personalized campaigns on KURTA and DRESS first, as these represent the highest sales volume and therefore the greatest impact on the 20% growth target.


Part 7 — Recommendations

To increase sales by 20% within 6 months, three actions are required — in priority order:

1. Fix delivery time (Highest priority)
Guarantee delivery within 3 business days. This is the single biggest reason customers choose competitors. Negotiate a new SLA with the logistics supplier or switch to a faster provider.

2. Improve product accuracy
Ensure all product descriptions match what is actually delivered. Add real product photos and accurate size guides. This directly reduces return rates and builds trust.

3. Simplify the return process
Include a return label in every package. Offer free returns on the first purchase. A frictionless return policy increases willingness to buy, especially from new customers.

4. Personalize follow-up campaigns
Replace generic discount emails with personalized recommendations based on purchase history. Focus campaigns on KURTA and DRESS — the two highest-volume categories.


Summary

AreaCurrent StateTarget StateDelivery5–7 daysMax 3 business daysReturnsComplicated, no labelFree first return, label includedProduct accuracyInconsistent100% accurate descriptions and photosCampaignsGeneric discountsPersonalized by purchase historySalesDeclining (–20%)+20% within 6 months


Project created by Deeqsi Nuuh as part of a self-directed Business Analysis portfolio.
Tools used: Lucidchart (process mapping), Excel (data analysis), GitHub (documentation)
