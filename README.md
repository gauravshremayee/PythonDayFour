# PythonDayFour
Python Day-4 or Session-4 Program

#Python filter function 

ages = [5, 12, 17, 18, 24, 32]

def myFunc(x):
  if x < 18:
    return False
  else:
    return True

adults = filter(myFunc, ages)

for x in adults:
  print(x)

#Python list comprehension 

#List comprehensions provide a concise way to create lists. 

new_list = []
for i in old_list:
    if filter(i):
        new_list.append(expressions(i))
You can obtain the same thing using list comprehension:
new_list = [expression(i) for i in old_list if filter(i)]




#Python lambda function 
#lambda function is small anonymous function

x = lambda a : a + 10
print(x(5))

# Take a list of numbers.  
my_list = [12, 65, 54, 39, 102, 339, 221, 50, 70, ] 
  
# use anonymous function to filter and comparing  
# if divisible or not 
result = list(filter(lambda x: (x % 13 == 0), my_list))  
  
# printing the result 
print(result)  

