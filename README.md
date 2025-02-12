a=float(input("cost of Item 1: "))
b=float(input("cost of Item 2: "))
c=float(input("cost of Item 3: "))
d=a+b+c
e=d*10/100
if(d>50):
 print(f'{d-e :.2f}')
else:
 print(f'{d:.2f}')
