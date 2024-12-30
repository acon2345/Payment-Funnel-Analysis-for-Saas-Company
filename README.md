# Payment Funnel Analysis for Saas Company

## Executive Summary:

The company has recognized that a significant number of subscriptions remain unpaid, indicating an obstacle in the online payment process, which has greatly impacted revenue negatively.
This analysis examines and identifies pain points within the online payment process and supply actionable recommendations to improve the converstion rate of successful payments.
Using SQL and a data science notebook to build a payment funnel analysis, I recommend the following be implemented to achieve the desired conversion rate:

1. 3rd party collaboration to indentify and devise a plan to resolve pain points
2. Reminder emails/texts/notifications to complete payment process
3. Utilizing technology to combat user error in payment method process


## Business Problem:

The finance team has recognized that many subscriptions haven't been paid which indicate a breakdown within the online payment process. For the desired conversion rate to be achieved, the product team must discover what friction points in the online payment process exist and what adjustments can be made to encourage users to successfully complete the online payment process.
<div class='tableauPlaceholder' id='viz1735526872990' style='position: relative'><noscript><a href='#'><img alt='Percent of Max Funnel Stage Reached ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;BD&#47;BDE-Project1_2&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='BDE-Project1_2&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;BD&#47;BDE-Project1_2&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>

## Methodology:
* EDA
* Product Funnel Analysis
* Data Visualization

## Skills:
* SQL
  * CTEs, Case, Subqueries, Window Functions
* Data Visualization
  * Tableau
* Data Wrangling
* Data Science Notebook
* Snowflake Data Warehouse

## Results & Business Recommendations

### Results:
After examining the data, it was found that 20.3% of subscriptions did not even start the payment process. Offering no chance for these to be converted.
Of those that at least started the payment process, 16.9% encountered an error somewhere in the online payment process. Some of these were able to continue on and complete the process but others not. Therefore, just encountering the error impacts the successful completion of the process.
<div class='tableauPlaceholder' id='viz1735526414391' style='position: relative'><noscript><a href='#'><img alt='Subscription No Error vs Error ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;BD&#47;BDE-Project1&#47;SubscriptionNoErrorvsError&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='BDE-Project1&#47;SubscriptionNoErrorvsError' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;BD&#47;BDE-Project1&#47;SubscriptionNoErrorvsError&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>

### Business Recommendations:
* Reach out to 3rd party payment processing vendors to inquire about the errors on their side and determine a plan to reduce those in the future.
* Due to a significant number of subscriptions not making it to at least the payment portal stage, work with the Product Manager to devise a plan on how to resolve this. Possibly have payment reminders or customer service agents reaching out to encourage payment.
* To help reduce user error due to incorrect payment info being entered, consider providing options such as Google Pay, Apple Pay, or other methods that don't require the user to enter the credit card manually each time.

## Next Steps:

* Investigate further to determine if user errors or vendor errors are more prevalent.
* Determine the cause of subscriptions not at least starting the online payment process.
* Measure email, text, and push notification open and click rates to determine which would be more effective.
