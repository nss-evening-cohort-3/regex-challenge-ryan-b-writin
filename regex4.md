Provide a regex that matches dates with the format: Wed Aug 11, 2013.  
  
-----  
[\w]{3}\s[\w]{3}\s[\d]{1,2}[,]\s[\d]{4}  

test strings   
Wed Aug 11, 2013  
Tue Jun 10, 2099  
Fri Mar 1, 1234  
