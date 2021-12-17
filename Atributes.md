Class Attributes 

It belongs to the class, however we can access it from the instance level.

```
class Item:
  pay_rate = 0.8 #The pay rate after 20% discount
  
  print(Item.pay_rate) #To access the attribute
  ```
  
  To access the attribute, It checks whether it is available in the Instance level and then in the class level.
