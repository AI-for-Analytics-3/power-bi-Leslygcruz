### Using CHATGPT for assistance with DAX

Here is a link to Housing Data https://drive.google.com/drive/folders/1Adn2w-4C8uUhTQU2f9ct_e8VcubzTP9i?usp=sharing

Open PowerBI and add these files.

-- You will be using ChatGPT to help you write DAX to alter some tables to make a PowerBI dashboard.

1. Open PowerBI and bring in the sheets for redfin_sales and interest_rates.*

2. In the model view we can see there are no columns to join on.  However we could make a MM/YYYY column in each table and join on that.*

3. Extract the month from the date column in the redfin_sales table and add it to a  new column. Then, create a month_year column from the month column and the year column.*

4. Create a monthy_year column in the interest_rates table.*

5. Now, we want to create a composite column in both tables with the format 'month, YYYY'.  Use this to form a relationship between the tables.*

6. Each row of the interest_rates table has the interest rate for that date. We want a single interest rate value for each month/year combination.*

7. We want an updated affordability score for every month of data.  First, ask ChatGPT some suggestions for good formulas for this.  There are many options. We are going to use a monthly payment calculator.  You want to create a monthly payment column rounded to 2 decimal places.*

8. We also want to get a month by month inventory pressure score.  0 should show a stable inventory, a positive number should mean inventory is growing, and a negative number should mean inventory is shrinking.*

9. We want to use DAX to create a new Date table that contains columns for Quarter and Quarter Year as well as a Month Year column to make a relationship with our existing tables.*

10. You can check that your connection works by creating a visualization using the date table for the X-axis and the affordability index for the Y-axis. You May need to create a new column in your Date table to sort by. 