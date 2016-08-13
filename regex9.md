Provide two regexes that matches  
NSS Evening Cohort 3  
and captures "Cohort 3".
  
-----  
[\w\s]{12}(\w+\s\d)
[\w]{3}[\s][\w]{7}[\s](\w{6}\s\d)

test string:
NSS Evening Cohort 3
