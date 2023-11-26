# MAIN-ANALYSIS-TYPES: FUNNELS AND A/B TESTS

**GRADED TASK**

-----

**You have a follow up task from your marketing manager.**

She does not trust the A/B test data you calculated previously looking at **“NewYear”** and **“BlackFriday”** campaigns and testing if versions had significantly different clickthrough rate **(Clicks/Impressions).** 

She thinks that the clicks were not tracked properly and those numbers are wrong, though she trusts that number of impressions are correct.

**She asks you to come up with an alternative way** to estimate how many people actually clicked on those banners from marketing **“NewYear”** and **“BlackFriday”** campaigns. 

**You remember** that you also have website tracking data in "turing_data_analytics.raw_events" table and you decide to estimate the number of users who clicked on marketing campaigns banners from this data, by calculating unique users who had at least one page view. 

So you join your original data of marketing campaigns from "turing_data_analytics.adsense_monthly" with this table and replace original clicks tracked by adsense data with your new estimate - the number of unique users these marketing campaigns brought to your website.

-----

**Task requirements**

**1.** You should prepare **SQL query** which would pull all data needed and similarly as before estimate if different variants of marketing campaigns (V1 vs V2) for both **“NewYear”** and **“BlackFriday”** campaigns had significantly better clickthrough rates **(estimated as: number of users who clicked on campaign / number of impressions).**

For now you can ignore timing of user tracking data, you do not need to check if those sessions were recorded when the marketing campaign was running.

**2.** Run the A/B testing on the results from your query.

* You can use Binomial A/B test Calculator.
* Bonus points if you create your own/custom A/B testing for this exercise.

**3.** Add visualizations to help illustrate A/B testing results.

-----


**Evaluation criteria:**

**1.** SQL, correct columns identified to make analysis.

**2.** Correctly calculated estimate for clickthrough rates.

**3.** Correctly performed A/B tests for both marketing campaigns.

**4.** Google Sheets data visualizations are included.

**5.** Analysis, findings and main points clearly structured.

**6.** Analytical approach to the problem

-----

**THE PROJECT**

**FUNNEL**   

https://docs.google.com/spreadsheets/d/15sBvWFoGjzX9pzY80FdroemyRBHOMNxm2TSgqc2txuk/edit#gid=67394685

**A/B TEST FOR NEW_YEAR**  

https://docs.google.com/spreadsheets/d/17DKRjJmxPFCPteHJWae25GISbsjVf97ld7R0LAcIUpQ/edit#gid=745822599

**A/B TEST FOR BLACK_FRIDAY**   

https://docs.google.com/spreadsheets/d/1HAZ6eBZRZxvMfHROkrRFrJv9MCV71D88eiGdYuDPrTE/edit#gid=745822599
