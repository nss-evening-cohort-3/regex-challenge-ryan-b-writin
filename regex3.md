Provide a regex that matches URLs like https://regex101.com, http://facebook.com  
and https://www.godaddy.com but not https://msdn.microsoft.com. (Trailing / should be allowed and optional)  
  
-----  
[htp]{4}[s]*[:\/]{3}[^m]{1}[\w\.]+  

test strings  
https://regex101.com  
http://facebook.com  
https://www.godaddy.com  
https://msdn.microsoft.com  
