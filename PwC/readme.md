# Telecom Customer Churn Analysis

Our client MegaTel, a leading telecommunications company, is facing a growing issue with customer churn. Their current method with this problem is reactive which only reach out to customer after they've already canceled their service. Unfortunately this approach isn't working well since they couldn't prevent customer from leave them.

Furthermore, their attempts at analyzing customer data using Excel haven't been very helpful, and it's hard for management to grasp the insights they need from these analysis.

### Project Goals
Based on explanation we concluded the project goals 
1. Identify customers who churned
2. Develop a proactive customer retention strategy to identify and address customer needs before they churn
3. Implement data visualization tools to create clear and actionable insights for management.

### Project Deliverables
* Interactive dashboards that visually represent customer insight and retention strategies

### Data
This dataset is provided by PwC through Forage virtual intership. Please refers to their website to get access for the dataset

## Visualization
Through our visualizations, we have uncovered significant findings, we divide it into two parts customer churn analysis and customer risk analysis.
### Customer Churn Analysis
We initiated our analysis by filtering the dataset to identify customers who have churned, providing insights into their behavior and preferences.
![customerchurn](Pictures/CustomerChurn.jpg)

Demographic Insight:
1. MegaTel has lost 1869 customers or 27% their customer last month.
2. By demographic, most of customers who churned is do not have partner and dependents. This could be indicate that MegaTel services doesn't give customer great experience for individual customers.
3. 55% of churned customer only signed up their services for less than 1 years where 20% already churn on the first month of transaction.

Usage Pattern Insight:
1. 91% of lost customers were signed up for phone services, but there's no significant differences for customer who signed up for multiple line and not.
2. By internet services, 69% signed up Fiber Optic, and the second place is DSL with 25% subscriber. This could indicate that Fiber optic services not give customers good experience or the price is expensive for the services.

Customer account insight:
1. By contract type, 89% customer use month-to-month contract. This findings is on a line with the fact that most of customer leave before 1 year of subscription. 
2. By payment method type, 57% customer use Electronich check to pay their bills.

### Customer Risk Analysis
After we identified customers who already leave, we could use the data to identify customers at risk.
![CustomerRisk1](Pictures/CustomerRisk1.jpg)

**Insight**
1. Customer in one year period of subscription is highly would leave the service and the percentage of leaver is decrease over period.
2. Seems there is a problem with Fiber Optic services, since the services has the highest number of opened ticket and the highest churn rate rather than another internet services and phone services. By evaluate the price, fiber optic is the most expensive one. It seems customer do not find the price worth with the services has been give.
3.  

![CustomerRisk2](Pictures/CustomerRisk2.jpg)
**Insight**
1. Contrary to expectations, our analysis reveals that despite monthly contracts offering lower charges, they exibit the highest churn rates compared to other subscription options. This indicates that factors beyong pricing, such as flexibility or customer preferences heavily influence subscription decisions and subsequent churn rates. **This insight emphasize the need to explore non-price-related factores when devising retention strategies**

2. Despite not being driven solely by charges, it's significant to note that fiber optic services, which boast the highest average monthly fees, coincide with a notable volume of tecnical support tickets opened. **This correlation may indicate potential dissatisfaction with the services quality provided**.

3. Our examination of contract types distribution unveils a suprising trend: even customers subscribed for a 2 and 3-year period predominantly opt for monthly contracts. **This suggests potential dissatisfaction with the provided services, possibly leading to subscription cancellations**


