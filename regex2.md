Provide a regex that matches valid phone numbers with the forms 678-123-1122 and (678) 123-1122  
while still allowing symbols to be optional. HINT: Research the rules around valid phone numbers.  
  
-----  
[(]*\d{3}[-)\s]*\d{3}[-]\d{4}  

test strings  
(123) 456-7890  
123-456-7890  
