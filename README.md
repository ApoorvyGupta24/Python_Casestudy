#Calculate the total cost of 3 different items.Add a discount of 10%
if the
#total exceeds $50
a=int(input("Cost of 1st item="))
b=int(input("Cost of 2nd item="))
c=int(input("Cost of 3rd item"))
sum=a+b+c
if(sum>=50):
 discount_price=sum*0.1 #dicount of 10%
 sum=sum-discount_price
print("total cost=",sum)
