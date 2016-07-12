Master Database

Column A
Contains ID Number as a string that will be modified with suffixes to represent IDs of rows in other databases releated to that specific customer.

Column B 
String Datatype of Customer Name

Column C 
String Datatype of Account Number

Column D 
Double Datatype of Account Balance

Column E 
Boolean Value of Margin Permissions

Column F 
Boolean Value of Forex Eligibility

Column G 
Boolean Value of whether or not there is a margin call on current account.

Customer Details

Column A
Same ID number appended with a suffix of -1 to reference contact details of customer.

Columns B-E 
Self explainitory string values of contact details

Column F

Boolean value that mirrors margin call value in masters spreadsheet so customer can be flagged on contact form as needing to be contacted.

Holdings

Column A

Same ID number as in other tables.  This time with each row appended to either a ticker for a security the customer is holding, or CASH or BAL, to display free cash in the account or display total balance (Sum of all Holdings)

Column B
String of Ticker Symbol null for cash or account balance

Column C
String of description of symbol

Column D
Price per share of each security

Column E
Number of shares Held

Column F
Current market value

