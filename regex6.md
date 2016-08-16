Provide a regex that matches   
```
function returnOne() {return 1;}  
```
and captures the value returned.
  
-----  
[\w\s()]+[{return\s]{8}(\d)[;}]{2}

test string:
function returnOne() {return 1;}
