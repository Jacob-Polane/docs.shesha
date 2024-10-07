# How to apply filters on dates

Displaying data from a predefined time range, like "Last 7 days" or "This month."

1. After adding the [Table View Selector](https://docs.shesha.io/docs/front-end-basics/form-components/data-display/data-table/table-view-selector)

   ![table view selector](https://github.com/user-attachments/assets/deb3e9bd-bd68-4e4f-b3ec-8df1e196b3bb)

   
2. Click on add filter on the property setting side panel
3. Click on the gear icon to configure the filter

   ![gear icon](https://github.com/user-attachments/assets/16ec488b-eb67-4043-a3a8-d38420c57d26)

   
4. Add  a rule to the filter
   - Select the property you will apply filter to (must be of type date). Check *Figure 2*
   - Select Operator (<,<=, == etc...)
   - Click the ellipsis next to the operator and select which value source you want to use (value, field and function Check *Figure 3*)
       1. Select value if a static date is to be used.
       2. Select field if you would like to compare to an existing property.
       3. Select function if the a customised function is to be used.
   - Configure the filter and save the filter

## Filtering using a custommised date :

![add rule](https://github.com/user-attachments/assets/5177da87-7005-427e-bb25-431e3def6a67)

*Figure 1*

![select property](https://github.com/user-attachments/assets/9c88db1f-fbd7-4e2b-b404-5f2c206bf66a)

*Figure 2*

![select value source](https://github.com/user-attachments/assets/99a2f988-279a-4a18-8df6-6ae680842fe2)

*Figure 3*

After selecting the function value source there are 3 options (now, relative, Evaluate)
1. Now : Select this option to filter data based on your chosen property and the current date.
2. Relative : Select 'Relative' to use the current date with an added or subtracted time interval.
3. Evaluate : Select 'Evaluate', you can use mustache syntax to dynamically embed values into your expressions. This allows you to insert variables, properties

For example, we can use the 'Relative' option to filter data for products created in the last seven days.

***Note:** A negative sign is used to filter past dates.*

![image](https://github.com/user-attachments/assets/056071e4-9c3b-41ad-8cec-0d2f2f309df9)






