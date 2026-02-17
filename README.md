numbers=list(map(int,input("Enter numbers: ").split()))
n=len(numbers)
for i in range(n):
    for j in range(0,n-i-1):
        if numbers[j]>numbers[j+1]:
            numbers[j],numbers[j+1]=numbers[j+1],numbers[j]
print("Sorted:",numbers)
Output
Enter numbers: 5 3 8 1
Sorted: [1, 3, 5, 8]
