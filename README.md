# SWISH-TechnicalCheck
This code is for SWISH Online recruitment test.

Inorder to get the total amount required to get a free coffee with discounts from second order, Original price must be decreased to p% of the previous amount paid for coffee.
temp=(int)(temp*((float)(100-p))/100); calculates the new discounted amount for present coffee. This must be added to the previous sum.
Hence, sum=sum+(int)(temp*((float)(100-p))/100); calculates the required sum amount to be paid.
At the end of loop, sum holds the required answer.
