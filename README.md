# 24-02-2022-Assignment-01
l=[]

y=int(input("enter range"))

for i in range(y):

    x=int(input("enter elements"))

    l.append(x)

print("ur list is:",l)

print("even numbers are:")

for i in l:

    if(i%2==0):

        print(i,end=" ")

print()

print("\nodd  umbers are")

for i in l:

    if(i%2!=0):

        print(i,end=" ")

print()
