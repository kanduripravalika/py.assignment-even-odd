# py.assignment-even-odd

# case 1:display no.of even and odd numbers in a series

int =(1,2,3,4,5,6,7,8,9)
count_odd=0
count_even=0
for i in int:
    if  i%2==0:
        count_even+=1
    else:
        count_odd+=1
print("number of even numbers :",count_even)        
print("number of odd numbers :",count_odd)        
