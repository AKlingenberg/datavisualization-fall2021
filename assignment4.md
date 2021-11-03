## Assignment 4

[Full Data Set](https://github.com/AKlingenberg/datavisualization-fall2021/blob/main/Klingenberg_Assignment4_fulldata.csv)
  (each individual pivot table is linked below)


### How I cleaned:

* I download the CSV file and opened it in excel
* I deleted any columns that did not have any information in them
* I evaluated columns where some rows had blanks and decided if the blanks were correct or if they were just missing data and subsequently deleted rows that were missing data
* I created my pivot table to start analyzing and asking questions
* To make the pivot table, I selected the entire data set using the “command + a” shortcut
* I clicked insert at the top of the excel window, and then clicked on the Tables options and chose a Pivot table. 
* I created three pivot tables so that I could have one for each question I was asking the data so that I could retain each answer individually. 
* For each question, I dragged the field name under “rows” and “values”. I was looking for the count of each field name for different questions, so if needed, I changed the value to show count rather than sum. 
  * For question 1, I dragged VIOLATION_PROCESS_DESCRIPTION
  * For question 2, I dragged FINE_AMOUNT → for this one I had to change sum to count
  * For question3, I dragged ACCIDENT_INDICATOR
* I sorted the pivot tables to show the data in greatest to least value order and found the answers

### Questions:

 1. [Which moving Violation Process occurred the most?](https://github.com/AKlingenberg/datavisualization-fall2021/blob/main/Klingenberg_Assignment4_question1.csv)
  Speed 11-15 MPH over the speed limit
 2. [Which fine amount was most often issued?](https://github.com/AKlingenberg/datavisualization-fall2021/blob/main/Klingenberg_Assignment4_question2.csv)
  $100 was the most commonly fined amount for moving violations
 3. [How many moving violations fines have not been paid?](https://github.com/AKlingenberg/datavisualization-fall2021/blob/main/Klingenberg_Assignment4_question3.csv)
  61,137 moving violations have not been paid 
  
 ### Sample Story
 
 DC Moving Violation Fines Go Unpaid

During the month of September, 70,458 moving violations were fined in DC. Out of them, 61,137 have still not been paid. The vast majority of tickets are going unpaid. This dramatic statistic highlights potential issues with individuals being able to afford tickets. The longer a ticket is outstanding, the more expensive it gets, which perpetuates the issue.

