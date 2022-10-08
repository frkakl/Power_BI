# Power_BI
 Learning Power BI step by step

DAX Codes;

WEEKDAY('Apocolypse Sales'[Date Purchased],2) => Transform Date to day.

Order_Size = IF('Apocolypse Sales'[Units Sold] > 50, "Big Order","Small Order") => Classic if-else statement, (Condition, True, False)

Profit_Column = SUMX('Apocolypse Sales', ('Apocolypse Store'[Price] - 'Apocolypse Store'[Production Cost] ) * 'Apocolypse Sales'[Units Sold]) => SUMX, sum in just one row.

SUM => Like Excel, sum all of item in column.
