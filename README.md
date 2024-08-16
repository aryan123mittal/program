# Reverse an array in python


# Method 1
array = [1,2,3,4,5]
array.reverse()
print(array)


# Method 2
#intialize the array
a=[1,2,3,4,5]
print("The array is ",a)
#get the size of array
l=len(a)
#go through the array half
for i in range(l//2):
#swap the elements
    a[i],a[l-i-1]= a[l-i-1],a[i]
print("The reverse of array is ",a)
