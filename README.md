# PythonArrayImplementation
#Python Array Implementation
#methode & Function

#Defining and declaring and array
arr = [10, 20, 30, 40, 50, 60]
print(arr)

#Accessing Array element
print(arr[0])
print(arr[1])
print(arr[2])
print(arr[3])
print(arr[-1]) #Negative index
print(arr[-2]) #Negative index

brands = ["Apple", "HP", "Microsoft", "Googe", "Dell"]
print(brands)

#Finding the length of the array
num_brands = len(brands)
print(num_brands)
#append() To add element to the end of the list
brands.append("Intel")
print(brands)

#extend() To extend all element of a list to the another list
my_list = ['geeks', 'for', 'geeks']
another_list = [6, 0, 4, 1]
my_list.extend(another_list)
print(my_list)
#insert() To insert an element at the another index
list3 = [ 1, 2, 3, 4, 5, 6, 7 ]
print(list3)
list3.insert(4,10)
print(list3)
#remove() To remove an element from the list
color = ["Red", "Blue", "Green", "White", "Yellow"]
print(color)
del color[4]
print(color)
color.remove("Green")
print(color)
#pop() To remove element return element at the given index
color = ["Red", "Blue", "Green", "White"]
print(color)
color.pop(1)
print(color)
#clear() To remove all element from the list
text1 = {1: "geeks", 2: "for"}
text1.clear()
print(text1)
#index() To return the index of the first matched element
list2 = ['cat', 'bat', 'mat', 'cat', 'pet']
l = list2.index('bat')
print(l)
#count() To count of number of element passed as an argument
fruits = ["apple", "banana", "cherry", "apple"]

x = fruits.count("apple")

print(x)
#sort() To sort the element in ascending order by default
letter1 = ['D', 'C', 'B']

letter1.sort()

print(letter1)
#reverse() To reverse oreder element in a list
str1 = ["A", "B", "C", "D", "E"]
print(str1)
str1.reverse()
print(str1)
#copy() To return a copy of element in a list
list1 = [ 1, 2, 3, 4 ]
print(list1)
list2 = list1.copy()
print("The new list is: " + str(list2))
#Modifying element of an aray using indexing
letter = ["A", "B", "C", "D", "E", "F"]
print(letter)
letter[1] = "G"
print(letter)
letter[-2] = "M"
print(letter)

#Concatenating two array uisng the + operator
concat = [2, 4, 6]
concating =concat + [8, 10, 12]
print(concating)

#Repeating element in an array
repeat = ["20"]
repeat = repeat * 10
print(repeat)

#Slicing an array

fruits = ["apple", "banana", "mango", "grapes", "orange"]
print(fruits)
print(fruits[0:4])
print(fruits[1:4])
print(fruits[ : 3])
print(fruits[-4 : ])
print(fruits[-3 : -1])

#Declaring and defininfng multidimentional array
mult = [[1,2], [3,4], [5,6], [7,8]]
print(mult)
print(mult[0])
print(mult[3])
print(mult[2][1])
print(mult[3][0])
