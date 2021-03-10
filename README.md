Description about data columns:
There are altogether 21 columns in our data set.All the  variables /factors  decide the approval of the loan or not.
Now let us look in to the each variable and can make some assumptions.(It’s just assumptions right, there is no harm in just assuming few statements)
ID- As the name suggests each person should have a unique loan id
Personal Details- city,sex,age, social calss. We can assume that These factors are not going to affect the approval of loan .
House Details- home_ownership, type_of_house, occupants_count, house_area , sanitary_availability, water_availability .We can assume that better house, less occupants , big house area ,good sanitary availabilty and water availabilty would increase the probability of  loan approval.
Financial Details- primary business, secondary business, annual income, monthly expenses, old dependents, young dependents. We can assume that  the person who have good  annual income,less monthly expenses ,less dependents, good primary business and having secondary business would have high probability of clearing loan amount and would be highly eligible for loan  .Here dependents means the no. of people dependents on the applicant who has taken loan has been provided. 
Loan Details- Loan purpose, loan tenure, loan installments, loan amount. Loan tenure represents  the number of months required to repay the loan.Loan amount

Loan Amount -> This amount represents the loan amount in thousands. One assumption I can make is that “ If Loan amount is higher , the probability of repaying would be lesser and vice versa”
Loan_Amount_Term -> This represents the number of months required to repay the loan.
Credit_History -> When I googled it , I got this information. A credit history is a record of a borrower’s responsible repayment of debts. It suggests → 1 denotes that the credit history is good and 0 otherwise.
Property_Area -> The area where they belong to is my general assumption as nothing more is told. Here it can be three types. Urban or Semi Urban or Rural
Loan_Status -> If the applicant is eligible for loan it’s yes represented by Y else it’s no represented by N.
Exploratory Data Analysis
Well don’t get to worry about the fancy names like exploratory data analysis and all. By looking at the columns description in the above paragraph, we can make many assumptions like
