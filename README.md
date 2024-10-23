
# loop list

mylist = ["kemal", "mehmet", "sıla", "sevi"]

for x in mylist:
    print(x)


# range(), len()
for i in range(len(mylist)):
    print(mylist[i])


# range(), len()
for i in range(1,2):
    print(mylist[i])



# while loop
mylist = ["kemal", "mehmet", "sıla", "sevi"]
i = 0
while i < len(mylist):
    print(mylist[i])
    i = i + 1



######################
# list comprehension
######################
mylist = ["kemal", "mehmet", "sıla", "ezgi"]
[print(x) for x in mylist]


# example
mylist = ["kemal", "mehmet", "sıla", "ezgi"]
newlist = []

for x in mylist:
    if "a" in x:
        newlist.append(x)

print(newlist)


# list comprehension example
mylist = ["kemal", "mehmet", "sıla", "ezgi"]
newlist = [x for x in mylist if "a" in x]
print(newlist)



# != not kemal
mylist = ["kemal", "mehmet", "sıla", "ezgi"]
newlist = [x for x in mylist if x != "kemal"]
print(newlist)


# iterable - range()
newlist = []
newlist = [x for x in range(9)]
print(newlist)


newlist = []
newlist = [x for x in range(1, 7)]
print(newlist)


# example
newlist = [x for x in range(10) if x < 5]
print(newlist)


mylist = ["kemal", "mehmet", "sıla", "ezgi"]
newlist = [x.upper() for x in mylist]
print(newlist)

mylist = ["kemal", "mehmet", "sıla", "ezgi"]
newlist = [x.capitalize() for x in mylist]
print(newlist)


# Andrew NG scientist

# example
fruits = ["apple", "kiwi", "cheery", "peanut", "banana"]
newlist = [x if x != "banana" else "orange" for x in fruits]
print(newlist)


# sort list - alphabetically
fruits = ["apple", "kiwi", "cheery", "peanut", "banana"]
fruits.sort()
print(fruits)


# sort numbers
numbers = [5, 2, 1, 4, 3]
numbers.sort()
print(numbers)


# sort descending
fruits = ["apple", "kiwi", "cheery", "peanut", "banana"]
fruits.sort(reverse = True)
print(fruits)

# sort numbers
numbers = [5, 6, 2, 1, 4, 3]
numbers.sort(reverse = True)
print(numbers)


# case insensitive sort
# sort method is case sensitive
thislist = ["apple", "Kiwi", "cheery", "peanut", "Orange"]
thislist.sort()
print(thislist)


# perform a case-insensitive sort of the list
thislist = ["apple", "Kiwi", "cheery", "peanut", "Orange"]
thislist.sort(key = str.lower)
print(thislist)


# copy a list
thislist = ["apple", "Kiwi", "cheery", "peanut", "Orange"]
mylist = thislist.copy()
print(mylist)

# another way to make a copy is to use list() method
thislist = ["apple", "Kiwi", "cheery", "peanut", "Orange"]
mylist = list(thislist)
print(mylist)


# example
thislist = ["apple", "Kiwi", "cheery", "peanut", "Orange"]
mylist = thislist[:3]
print(mylist)


# python join list

thislist = ["apple", "Kiwi", "cheery", "peanut", "Orange"]
numbers = [5, 6, 2, 1, 4, 3]
list3 = thislist + numbers
print(list3)




# append() method
thislist = ["apple", "Kiwi", "cheery", "peanut", "Orange"]
numbers = [5, 6, 2, 1, 4, 3]

for x in numbers:
    thislist.append(x)

print(thislist)


# extend()
thislist = ["apple", "Kiwi", "cheery", "peanut", "Orange"]
numbers = [5, 6, 2, 1, 4, 3]

thislist.extend(numbers)
print(thislist)


# tuples
mytuple = ("apple", "Kiwi", "cheery", "peanut", "Orange")

# unchangeable
# ordered
# tuples are written with round brackets
# tuple items are indexed, fist index 0, the second index is 1
# allow dublicates

mytuple = ("apple", "apple", "kiwi", "cheery", "peanut", "orange")
print(mytuple)

# tuple length
print(len(mytuple))


# create tuple with one item
thistuple = ("kemal",)
print(type(thistuple))


# tuple items can be any data type
# string, int, float, boolean
tuple1 = (True, False, True) # boolean
tuple2 = (1, 2, 3, 4) # int
tuple3 = ("apple", "apple", "kiwi")

# a tuple can contain different data types
tuplelistem = ("kemal", 99, True, 22, "kedi")
print(tuplelistem)
type(tuplelistem)



# tuple() constructor
mytuple = tuple(("kemal", "mehmet"))
print(mytuple)


# access tuple items
mytuple = ("apple", "apple", "kiwi", "cheery", "peanut", "orange")
print(mytuple[3])

# negative index
mytuple = ("apple", "apple", "kiwi", "cheery", "peanut", "orange")
print(mytuple[-2:])


# range of index
mytuple = ("apple", "apple", "kiwi", "cheery", "peanut", "orange")
print(mytuple[2:5])


# range of index
mytuple = ("apple", "apple", "kiwi", "cheery", "peanut", "orange")
print(mytuple[:3])

# range of index
mytuple = ("apple", "apple", "kiwi", "cheery", "peanut", "orange")
print(mytuple[3:])



# check if item exist
mytuple = ("apple", "apple", "kiwi", "cheery", "peanut", "orange")
if "apple" in mytuple:
    print("yes, 'apple' is in the list")


# change tuple items
x = ("apple", "apple", "kiwi", "cheery", "peanut", "orange")
type(x) # tuplemış

y = list(x)
type(y)

x = tuple(y)
type(x)


print("hi")






# loop list

mylist = ["kemal", "mehmet", "sıla", "sevi"]

for x in mylist:
    print(x)


# range(), len()
for i in range(len(mylist)):
    print(mylist[i])


# range(), len()
for i in range(1,2):
    print(mylist[i])



# while loop
mylist = ["kemal", "mehmet", "sıla", "sevi"]
i = 0
while i < len(mylist):
    print(mylist[i])
    i = i + 1



######################
# list comprehension
######################
mylist = ["kemal", "mehmet", "sıla", "ezgi"]
[print(x) for x in mylist]


# example
mylist = ["kemal", "mehmet", "sıla", "ezgi"]
newlist = []

for x in mylist:
    if "a" in x:
        newlist.append(x)

print(newlist)


# list comprehension example
mylist = ["kemal", "mehmet", "sıla", "ezgi"]
newlist = [x for x in mylist if "a" in x]
print(newlist)



# != not kemal
mylist = ["kemal", "mehmet", "sıla", "ezgi"]
newlist = [x for x in mylist if x != "kemal"]
print(newlist)


# iterable - range()
newlist = []
newlist = [x for x in range(9)]
print(newlist)


newlist = []
newlist = [x for x in range(1, 7)]
print(newlist)


# example
newlist = [x for x in range(10) if x < 5]
print(newlist)


mylist = ["kemal", "mehmet", "sıla", "ezgi"]
newlist = [x.upper() for x in mylist]
print(newlist)

mylist = ["kemal", "mehmet", "sıla", "ezgi"]
newlist = [x.capitalize() for x in mylist]
print(newlist)


# Andrew NG scientist

# example
fruits = ["apple", "kiwi", "cheery", "peanut", "banana"]
newlist = [x if x != "banana" else "orange" for x in fruits]
print(newlist)


# sort list - alphabetically
fruits = ["apple", "kiwi", "cheery", "peanut", "banana"]
fruits.sort()
print(fruits)


# sort numbers
numbers = [5, 2, 1, 4, 3]
numbers.sort()
print(numbers)


# sort descending
fruits = ["apple", "kiwi", "cheery", "peanut", "banana"]
fruits.sort(reverse = True)
print(fruits)

# sort numbers
numbers = [5, 6, 2, 1, 4, 3]
numbers.sort(reverse = True)
print(numbers)


# case insensitive sort
# sort method is case sensitive
thislist = ["apple", "Kiwi", "cheery", "peanut", "Orange"]
thislist.sort()
print(thislist)


# perform a case-insensitive sort of the list
thislist = ["apple", "Kiwi", "cheery", "peanut", "Orange"]
thislist.sort(key = str.lower)
print(thislist)


# copy a list
thislist = ["apple", "Kiwi", "cheery", "peanut", "Orange"]
mylist = thislist.copy()
print(mylist)

# another way to make a copy is to use list() method
thislist = ["apple", "Kiwi", "cheery", "peanut", "Orange"]
mylist = list(thislist)
print(mylist)


# example
thislist = ["apple", "Kiwi", "cheery", "peanut", "Orange"]
mylist = thislist[:3]
print(mylist)


# python join list

thislist = ["apple", "Kiwi", "cheery", "peanut", "Orange"]
numbers = [5, 6, 2, 1, 4, 3]
list3 = thislist + numbers
print(list3)




# append() method
thislist = ["apple", "Kiwi", "cheery", "peanut", "Orange"]
numbers = [5, 6, 2, 1, 4, 3]

for x in numbers:
    thislist.append(x)

print(thislist)


# extend()
thislist = ["apple", "Kiwi", "cheery", "peanut", "Orange"]
numbers = [5, 6, 2, 1, 4, 3]

thislist.extend(numbers)
print(thislist)


# tuples
mytuple = ("apple", "Kiwi", "cheery", "peanut", "Orange")

# unchangeable
# ordered
# tuples are written with round brackets
# tuple items are indexed, fist index 0, the second index is 1
# allow dublicates

mytuple = ("apple", "apple", "kiwi", "cheery", "peanut", "orange")
print(mytuple)

# tuple length
print(len(mytuple))


# create tuple with one item
thistuple = ("kemal",)
print(type(thistuple))


# tuple items can be any data type
# string, int, float, boolean
tuple1 = (True, False, True) # boolean
tuple2 = (1, 2, 3, 4) # int
tuple3 = ("apple", "apple", "kiwi")

# a tuple can contain different data types
tuplelistem = ("kemal", 99, True, 22, "kedi")
print(tuplelistem)
type(tuplelistem)



# tuple() constructor
mytuple = tuple(("kemal", "mehmet"))
print(mytuple)


# access tuple items
mytuple = ("apple", "apple", "kiwi", "cheery", "peanut", "orange")
print(mytuple[3])

# negative index
mytuple = ("apple", "apple", "kiwi", "cheery", "peanut", "orange")
print(mytuple[-2:])


# range of index
mytuple = ("apple", "apple", "kiwi", "cheery", "peanut", "orange")
print(mytuple[2:5])


# range of index
mytuple = ("apple", "apple", "kiwi", "cheery", "peanut", "orange")
print(mytuple[:3])

# range of index
mytuple = ("apple", "apple", "kiwi", "cheery", "peanut", "orange")
print(mytuple[3:])



# check if item exist
mytuple = ("apple", "apple", "kiwi", "cheery", "peanut", "orange")
if "apple" in mytuple:
    print("yes, 'apple' is in the list")


# change tuple items
x = ("apple", "apple", "kiwi", "cheery", "peanut", "orange")
type(x) # tuplemış

y = list(x)
type(y)

x = tuple(y)
type(x)


print("hi")





