# Financial-Risk-Analytics Project
Problem Statement
Businesses or companies can fall prey to default if they are not able to keep up their debt 
obligations. Defaults will lead to a lower credit rating for the company which in turn reduces 
its chances of getting credit in the future and may have to pay higher interests on existing 
debts as well as any new obligations. From an investor's point of view, he would want to 
invest in a company if it is capable of handling its financial obligations, can grow quickly, and 
is able to manage the growth scale.
A balance sheet is a financial statement of a company that provides a snapshot of what a 
company owns, owes, and the amount invested by the shareholders. Thus, it is an important 
tool that helps evaluate the performance of a business.
Data that is available includes information from the financial statement of the companies for 
the previous year (2015). Also, information about the Networth of the company in the 
following year (2016) is provided which can be used to drive the labeled field.

Conclusion
The two approaches used gave quite different results.
The second approach – Model B (where the model was built using all the independent 
variables and then dropping those with p values > 0.05) gave a better model than the 
first approach (Model A) (where the highly correlated independent variables using the 
VIF criterion were excluded and then the model is built).
Model B is also simpler than Model A with only 6 independent variables (excluding the 
intercept term) compared to 12 for Model A.
Moreover, there are only 2 independent variables common between the two models, 
with a third one very close (Book_Value_Unit_Curr in Model B and
