# Limit-less-than-99999
n=int(input("Enter the limit less than 99999 "))
small=99999
for i in range(1,n+1):
    print("Enter",i,end='')
    a=int(input("th number:"))
    if a<small:
        small=a
        print("Smallest number is:",small)

OUTPUT:
Enter the limit less than 99999 4
Enter 1th number:5
Smallest number is: 5
Enter 2th number:2
Smallest number is: 2
Enter 3th number:1
Smallest number is: 1
Enter 4th number:6
