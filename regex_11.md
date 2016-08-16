Provide a regex (as if for a password checker), that enforces a password to have at least one symbol and one number.
  
-----  
.*(?=[!@#$%^&]+)(?=.*\d).*

test strings
dsagfdfg
dsagfdfg!2
2!sdadfhsdhfg2!
!2sdadfhsdhfg3%
