# Customer-Sales-Tax-Analysis
About the Project

This project was created in Microsoft Excel to organize and analyse customer sales data.

The worksheet contains information such as customer codes, customer names, tax categories, quantity sold, total weight, price totals, rice weight, tax percentage, and the final tax amount.

The main idea was to use Excel formulas to calculate the values automatically instead of working them out manually for every customer.

Technology Used

Microsoft Excel – Used to enter, organise, calculate, and analyse the data.

Excel Functions and Formulas – Used to calculate totals, tax amounts, and other values from the data.

Features and Insights

The worksheet makes it easier to see how much each customer bought and the financial value attached to each transaction.

Customer Information

Each row represents a customer and contains their:

Customer Code

Customer Name

Tax Category

Quantity Sold

This makes it easier to identify individual customers and compare their transactions.

Quantity and Weight

The Qty Sold and Total Weight columns show the amount of product sold and the corresponding weight.

From the data, the quantity sold varies quite a lot between customers. For example, some customers purchased more than 1,000 units, while others purchased fewer than 500.

This makes it possible to compare customers based on how much they purchased.

Price Information

The Price Total Kg column shows the total value associated with the customer's transaction.

The values vary from customer to customer, which gives a quick way to identify larger and smaller transactions.

Tax Calculation

The sheet also includes a Tax Amount column.

Most of the rows shown have a 10% tax, while some rows have 0%. This means the tax amount changes depending on the tax rate assigned to the transaction.

For example, where a transaction has a 10% tax rate, the tax amount is calculated from the relevant transaction value.

This helps reduce manual calculations and makes it easier to keep the tax figures consistent.

Overall Insight

One useful thing about this worksheet is that the calculations connect the different parts of the data together. Instead of just storing customer information, the sheet can be used to see the relationship between quantity, weight, transaction value, tax rate, and tax amount.

My Process

1. Entered the Data

I started by putting the customer and sales information into Excel and arranging it into separate columns.

2. Organised the Columns

I made sure each column had a clear purpose, such as customer name, quantity sold, weight, price, and tax.

Keeping the columns organised made the calculations easier to manage.

3. Checked the Data

I went through the rows to make sure the numbers were entered correctly and that the tax percentages were in the right format.

I also checked that the customer names and codes matched the correct transactions.

4. Used Excel Formulas

I used formulas to calculate values rather than entering the results manually.

For example, a basic tax calculation can be written as:

=Price_Total*Tax_Rate

If the price total is in column G and the tax rate is in column I, the formula could be:

=G2*I2

The formula can then be copied down the column so that Excel calculates the tax for each customer.

5. Checked the Results

After applying the formulas, I compared some of the calculated values with the original figures to make sure the results made sense.

What I Learned

This project helped me become more comfortable using Excel for basic data analysis.

I learned how to:

Organise raw data into a useful table.

Work with customer and sales information.

Use Excel formulas instead of doing calculations manually.

Calculate percentages and tax amounts.

Copy formulas down multiple rows.

Check whether calculated results are correct.

Use formatting to make financial data easier to read.

Understand how different columns can be connected through formulas.

One thing I found useful was seeing how a simple formula can save a lot of time when the same calculation needs to be done for many customers.

How It Can Be Improved

There are a few things I would add to make the worksheet more useful.

Add a Summary Section

A summary at the top could show:

Total quantity sold

Total weight

Total sales value

Total tax

Number of customers

Average transaction value

This would give a quick overview without having to go through every row.

Add Charts

Charts could be used to compare:

Sales by customer

Quantity sold by customer

Tax amount by customer

Weight by customer

This would make the information easier to understand visually.

Add Filters

Excel filters could be used to quickly find customers based on their tax category, quantity, or transaction value.

Use Excel Tables

Converting the data range into an Excel Table would make it easier to sort, filter, and extend the formulas when new customers are added.

Add Data Validation

Data validation could be used for fields such as the tax category and tax rate. This would reduce the chance of entering invalid values.

Common Errors

Incorrect Cell References

One of the easiest mistakes to make when using formulas is referencing the wrong cell.

For example, if the tax formula is supposed to use the price in column G but accidentally uses another column, the final tax amount will be wrong.

Wrong Tax Rate

A tax rate entered as 10 instead of 10% can produce a very different result.

It is important to make sure percentage values are formatted and entered correctly.

Copying Formulas Incorrectly

When copying formulas down a column, the cell references need to move correctly with each row.

If the wrong references are used, the formula may calculate using another customer's information.

Numbers Stored as Text

Sometimes numbers can be stored as text instead of actual numbers. When this happens, Excel may not calculate them properly.

Missing Values

Blank cells in important columns can affect calculations. Before analysing the data, I would check for missing values in fields needed for the formulas.

Incorrect Formatting

Currency, percentages, quantities, and weights should use the correct number formats. Good formatting makes the spreadsheet easier to read and helps prevent confusion.

Conclusion

This Excel project gave me practical experience working with customer and sales data and using formulas to automate calculations.

The main lesson I took from it is that Excel can make repetitive calculations much easier when the data is properly organised.

The worksheet can also be taken further by adding summary figures, charts, filters, data validation, and more advanced Excel functions. These improvements would make it more useful for analysing larger amounts of customer and sales data.
