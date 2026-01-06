# python-program-17
coding
L=[2,58,95,99,65,32,15,1,7,45]
n=int(input("Enter the number to be searches:"))
found=0
for x in L:
    if x==n:
        print("Item found at position:",L.index(n)+1)
        found=1
        if found==0:
            print("Item not found")
output
Enter the number to be searches:95
Item found at position: 3
