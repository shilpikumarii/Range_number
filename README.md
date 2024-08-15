# Range_number
#find range number takin user input
num=int(input("enter the range number:-"))
first_val=0
second_val=1
for n in range(0,num):
    if(n<=1):
        next=n
    else:
        next=first_val+second_val
        first_val=second_val
        second_val=next55
        print(next)
