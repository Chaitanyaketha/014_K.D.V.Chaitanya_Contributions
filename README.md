# 001_K.D.V.Chaitanya_Contributions
Python assignment programs
Ques:2
a=20
b=50
print("maximum of two numbers is:",max(a,b))
print('minimum of two numbers is:',min(a,b))
average= (a+b)/2
print('average of two numbers is:',average )
print("addition of two numbers is:",(a+b))
print("multiplication of a and b is:",(a*b))

Ques3:
list=[62,17,1,6,81,716,'sairam',56.61,6]
print('the list in reverse order is:',list[::-1])

Ques4:
tup = eval(input("Enter input for tuple:")) 
tup2 = () 
tup3 = ()
i = 0 
while i < len(tup): 
  if i % 2 == 0: 
    tup2 += (tup[i],)  
  else: tup3 += (tup[i],) 
  i += 1
print(tup2) 
print(tup3)
