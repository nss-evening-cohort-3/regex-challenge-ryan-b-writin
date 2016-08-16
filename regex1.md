Provide three regexes that matches yes yes yes but not no no no  
  
-----  
1.[yes\s]+  
2.[^no]+  
3.[yes]+\s[yes]+\s[yes]+  

test strings  
1. yes yes yes  
2. no no no  
