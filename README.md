### Customer churn using survival analysis

- Customer churn is a term used in the industry to describe when customers cease doing business with a company or stop using its services. 
- Survival analysis is a statistical method that can be used to analyze customer churn data, which involves estimating the probability of a customer continuing to use a service over time.

In this R programming project, we will be using the Kaplan-Meier method of survival analysis to analyze customer churn data. We will be using the survival package in R to perform the analysis.

### The Tool: Survival Analysis
To do so, we’re going to borrow a tool from an unlikely place, survival analysis. Survival analysis was first developed by actuaries and medical professionals to predict survival rates.

Survival analysis works well in situations where we can define:

- A ‘Birth’ event: for our application, this will be a customer entering a contract with a company
- A ‘Death’ event: for us, ‘death’ is a customer ending a relationship with a company

The component that makes survival analysis superior to other regression models is its ability to deal with censorship in data.
