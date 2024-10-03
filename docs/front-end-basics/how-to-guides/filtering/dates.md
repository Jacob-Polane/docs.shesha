# How to apply filters on dates

Displaying data from a predefined time range, like "Last 7 days" or "This month."

1. After adding the [Table View Selector](https://docs.shesha.io/docs/front-end-basics/form-components/data-display/data-table/table-view-selector)

   ![image](https://github.com/user-attachments/assets/dd984ad1-ab70-4054-8554-037cefa99a52)
   
2. Click on add filter on the property setting side panel
3. Click on the gear icon to configure the filter

   ![image](https://github.com/user-attachments/assets/ea6d7687-4c6b-45a8-8b97-9871026bb3f7)
   
4. Add  a rule to the filter
   - Select the property you will apply filter to (must be of type date). Check *Figure 2*
   - Select Operator (<,<=, == etc...)
   - Click the ellipsis next to the operator and select which value source you want to use (value, field and function Check *Figure 3*)
       1. Select value if a static date is to be used.
       2. Select field if you would like to compare to an existing property.
       3. Select function if the a customised function is to be used.
   - Configure the filter and save the filter

## Filtering using a custommised date :

![image](https://github.com/user-attachments/assets/d8def4ac-20a1-4600-b1ed-b31edcd8fbe8)
*Figure 1*

![image](https://github.com/user-attachments/assets/ff064ee4-0f02-4f82-9b05-d04714fe755b)
*Figure 2*

![image](https://github.com/user-attachments/assets/45872715-9b1d-4edc-8a07-cbaaa6f78398)
*Figure 3*

After selecting the function value source there are 3 options (now, relative, Evaluate)
1. Now : Select this option to filter data based on your chosen property and the current date.
2. Relative : Select 'Relative' to use the current date with an added or subtracted time interval.
3. Evaluate : Select 'Evaluate', you can use mustache syntax to dynamically embed values into your expressions. This allows you to insert variables, properties

For example, we can use the 'Relative' option to filter data for products created in the last seven days.

***Note:** A negative sign is used to filter past dates.*

![image](https://github.com/user-attachments/assets/056071e4-9c3b-41ad-8cec-0d2f2f309df9)






