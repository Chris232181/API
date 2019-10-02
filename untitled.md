#### Financial Report

In this section, you will compile a financial report to demo your calculations to the consumer app team. The report should be written as a markdown file and include the following sections:

#### Budget Analysis

In this section, you will use the Plaid API to obtain transaction and account data for the budget analysis section of the report.

Follow the steps outlined in the budget starter notebook to complete the following:

1. Generate a Plaid access token to access the Developer Sandbox.



2. Use the Access token to fetch account transactions from the sandbox. You should fetch the last 90 days of transactions from the sandbox using the following institution:

    ```python
    INSITUTION_ID = "ins_109508"
    ```

3. Perform basic budget analysis on the sandbox transaction and generate the following plots:

* Spending Categories Pie Chart

  ![Expenses per category](Images/spending-pie.png)

* Spending Per Month Bar Chart

  ![Expenses per month](Images/spending-month.png)
  

4. Use the API to fetch income data from the sandbox and print the following:

* Last Year's Income Before Tax

* Current Monthly Income

* Projected Year's Income Before Tax

