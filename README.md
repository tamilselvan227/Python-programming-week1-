# Python-programming-week1-
1.
a=input()
b=input()
c=float(b)
d=round(c,1)
print(a,type(int(a)),sep=",")
print(d,type(d),sep=",")

2.
ramesh_salary=int(input())
dearness_allowance=(40/100)*ramesh_salary
rent_allowance=(20/100)*ramesh_salary
gross_salary=dearness_allowance+rent_allowance+ramesh_salary
print(int(gross_salary))

3.
import math

a=float(input())
b=math.sqrt(a)
print("{:.3f}".format(b))

4.
import math

a=float(input())
b=math.sqrt(a)
print("{:.3f}".format(b))

5.
cont1=int(input())
cont2=int(input())
refund1=cont1*0.10
refund2=cont2*0.25
refund=refund1+refund2
res="{:.2f}".format(refund)
print("Your total refund will be $",res,".",
