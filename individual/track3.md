## Deployment Plan for Churn Model

Churn predictions do not need to be generated instantly. Overnight batch scoring is sufficient because retention actions such as emails or outreach campaigns are typically planned ahead.

The model would run weekly on updated customer data and save the results into a database table that feeds a dashboard used by marketing and customer success teams.

At a high level, this would be implemented using a scheduled Python process that pulls data using SQL, runs the trained model, and writes predictions back to a reporting table.

To maintain trust in the model over time:

- Data quality check: verify row counts and check for missing values in key customer fields
- Input drift check: monitor whether important variables like monthly fee or engagement metrics shift significantly
- Outcome check: compare predicted churn risk with actual churn rates each month
