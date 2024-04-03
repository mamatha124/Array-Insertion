# Array-Insertion in python
n = int(input())
arr = [int(input()) for i in range(n)]
pos = int(input())
if pos > n:
    print("Invalid Input")
else:
    ele = int(input())
    print("Array after insertion is")
    for i in range(n):
        if i == pos - 1:
            print(ele)
        print(arr[i])
