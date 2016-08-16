Provide two regexes that matches the following C# code and captures the property names. 
(HINT: How could you match a newline?)
```
public class Part
{
    public string PartName { get; set; }
    public int PartId { get; set; }
}
```
  
---  
.*\n[{}]\n[\s]+[\w]+\s[\w]+\s(\w+).*\n[\s]+[\w]+\s[\w]+\s(\w+).*\n[}]

test string
```
public class Part
{
    public string PartName { get; set; }
    public int PartId { get; set; }
}
```
