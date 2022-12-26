# assignment-16-python
python
NumList = []
Number = int(input("How many element in list, please enter num :- "))
for i in range(1, Number + 1):
    value = int(input("Please enter the Value of %d Element : " %i))
    NumList.append(value)
 
NumList.sort()
 
print("The Smallest Element in this List is : ", NumList[0])
print("The Largest Element in this List is : ", NumList[Number - 1])
