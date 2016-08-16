Provide a regex that matches emails from the domains .com, .org, .net, .io and .ly 
but not .biz and .com.uk. This regex should capture the end result. (use #10 as a starting point).
  
-----  
[\w\d.]+[@][\w]+.[^z.]+

test strings:
sdgafs@gssfgs.com
sdgafs@gssfgs.org
sdgafs@gssfgs.net
sdgafs@gssfgs.io
sdgafs@gssfgs.ly
sdgafs@gssfgs.biz
sdgafs@gssfgs.com.uk
