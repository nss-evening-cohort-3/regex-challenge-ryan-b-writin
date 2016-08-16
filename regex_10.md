Provide a regex that matches emails of the forms 
```first.last@example.com``` and ```something99@history.com```
Allow for numbers in the domain name as well as the email prefix. Capture the domain name.
  
-----  
[\w\d.]+[@](\w+.\w+)

test strings:
asfasdf.asdfasdga@gsgggg.tttee
first.last@example.com
something99@history.com
