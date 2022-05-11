# datatype in python

'''
numbers(int, complex, float)
Sequence Type (string, tuple, list)
boolean
set
dictionary

'''

# numbers datatypes
'''
a = 5
b = 10.5
c = 4j

print(a)
print(b)
print(c)

print(type(a))
print(type(b))
print(type(c))

'''

# sequence type data type
'''
a = "ghaziabad"
b = ("mumbai", "delhi", "bhagalpur")
c = ["India", "Pakistan", "Nepal", "Sri Lanka"]

print(a)
print(b)
print(c)

print(type(a))
print(type(b))
print(type(c))
'''


#boolean datatype 
'''
x = True
print(x)
print(type(x))
'''


#set datatype
'''
c = {"India", "Pakistan", "Nepal", "Sri Lanka"}

print(type(c))
'''


#dictionary datatype
'''
dict= {'Brand':'Lamborghini','Model':'Sian', 'Colour':'Black'}
print("Car Brand",dict['Brand'] )
print("Car Model",dict['Model'])
print("Car Colour",dict['Colour'])
'''

# rules for making variables in python

'''
1. do not use space while making variables 
2. no special symbols
3. do not use numbers as first letter
4. invalid (my name = ""; , @name = "";)
5. valid(name = ""; , myname3 = ""; , my_name = "";)
'''

# invalid datatype
'''
my name = "Ayush"
n@me = "Ayush Mishra"
9list = "list"

print(my name)
print(n@me)
print(9list)'''

# valid datatypes 
'''
name = "Ayush"
myname3 = "Ayush Mishra"
my_name = "Ayush Pro"

print(name)
print(my_name)
print(myname3)
'''


# type casting
'''
x = str(5.55)
print(x)
print(type(x))

# invalid type casting
x = int("Ayush")
print(x)
print(type(x))
'''

# taking input and giving output from user

# taking input
'''
a = input("Enter a Number.\n")
print("You Entered : ",a)
'''

# Operators in python

# 1. Arithmetic Operators (+,-,/,*,%,//,**)
'''
x = 5
y = 4

print("The sum Of x and y is : ",x+y)
print("The difference Of x and y is : ",x-y)
print("The division Of x and y is : ",x/y)
print("The multiplication Of x and y is : ",x*y)
print("The percentage Of x and y is : ",x%y)
'''

#Assignment Operator(+=,-=,*=,/=,**=,=)
'''
x = 5
y = 8
'''
'''
x += 5
print(x)

x -= 5
print(x)

x *= 5
print(x)

x /= 5
print(x)

x **= 5 
print(x)

x = 5
print(x)





y += 8
print(y)

y -= 8
print(x)

y *= 8
print(y)

y /= 8
print(y)

y **= 8
print(y)

y = 8
print(y)
'''


#Comparison Operator (==,<=,<,>,!=)
'''
print("Comparison is : ", x==y)
print("Comparison is : ", x<=y)
print("Comparison is : ", x>=y)
print("Comparison is : ",x<y)
print("Comparison is : ",x>y)
print("Comparison is : ", x!=y)
print(type(x!=y))
print(type(x>y))
print(type(x<y))
print(type(x>=y))
print(type(x<=y))
print(type(x==y))
'''

# bitwise operator(^ , | , & , ~ , << , >>)
'''
x = 7
y = 2

print("The result is : ", x ^ y)
print("The result is : ", x | y)
print("The result is : ", x & y)
print("The result is : ", x << y)
print("The result is : ", x >> y)
'''

# membership operator ( in , not in)
'''
x = ["India", "Pakistan"]
print("Africa" not in (x))

y = ["Sri Lanka", "Nepal"]
print("Sri Lanka" not in (y))
'''


# identity Operator (is , is not)
'''
x = ["BMW", "LAMBORGHINI", "MARUTI"]
y = ["BMW", "LAMBORGHINI", "MARUTI"]
z = x

print(x is z)
print(x is y)
print(x == y)
'''


# if - else statement 
'''
print("Enter your age.")

age = int(input())

if age > 18 :
    print("You can drive car.")

elif age==18:
    print("You are just of 18 but you can drive car.")

else : 
    print("You cannot drive car.")
    '''

# loops (while , for)
#for loop
'''
a = 10
for a in range(1,100) :
    print(a)
    a+=1
'''
#while loop 
'''
i = 1
while i<=100:
    print(i)
    i+=1
'''

# list and tuples

#carlist = ["Toyota" , "Fortuner" , "Lamborghini"]

#print(carlist)
#print(type(carlist))
#carlist.insert(0, "Swift")
#print(carlist)
#carlist.remove("Fortuner")
#print(carlist)
#carlist.append("Scorpio")
#print(carlist)
#print(len(carlist))
#print(len(carlist[2]))
#carlist[0] = "Alto"
#print(carlist)
#carlist.sort()
#print(carlist)
#carlist.remove("Lamborghini")
#print(carlist)


# tuples 
'''
car8 = ("Maruti" , "Terzo" , "Tesla" , "Range Rovar" , "Buggati")
print(car8)
#print(type(car8))
#print(car8[2])
#car8 = list(car8)
#car8.append("Volvo")
#car8.insert(3, "Indigo")
#print(car8)
#new = tuple(car8)
#print(car8)
'''
# break and continue statement in python

'''
for var in "word":
    if var == "d":
        continue
    print(var)
        
        
    print("Ending")

'''
'''
for var in "India":
    if var == "a" : 
        break
print(var)
'''

# set in python

#set1 = {900,400,500,600}
#set2 = {200,100}
#print(set1)
#print(type(set1))

#set1.add(18)
#print(set1)
#set1.update(set2)
#print(set1)
#set1.remove(400)
#print(set1)
#set1.clear()
#print(set1)

# set union

#set1 = {100,200,300,400}
#set2 = {500,600,700}
#set3 = set1.union(set2)
#print(set3)


# intersection of sets  in python
'''
set1 = {900,80,70}
set2 = {900,800,700}
set3 = set1.intersection(set2)
print(set3)
'''

# numbers & strings

#print("Min(101,105,99,109)", min(101,105,99,109))
#print("Min(101,105,99,109)", max(101,105,99,109))


# strings 

#print("hello")
#print("hello")


#para = '''how is 
#this \n possible 
#are
#u'''

#print(para)


#text = "long live india"
#print("delhi"in text)


#a = "Ayush"
#b = " Mishra"
#c = a+b
#print(c)
#print(len(a))
#print(a[3])
#a = "Ashis"
#print(a)
#print(a.lower())
#print(a.upper())
#print(a.replace("A", "Z"))
#name = "Ayush"
#txt = "myname {}"
#name = input("")
#print(txt.format(name))
'''
txt = "We are Indians and\n we are proud to be an Indian" 
print(txt)'''




# functions 
'''
def add(x , y):
    return x+y

print(add(5, 6))

print(add(9, 4))'''

'''
def fun_nation (country):
    print("I am from "  +country)

fun_nation("India")'''

'''
def fun_admit(name,age,phone,city,country):
    print("My Name Is {0} his/her age is {1} number is {2} lives in {3} situated in {4} ".format(name, age, phone, city, country))


#fun_admit("Ayush", 14, 8758490242, "Bhagalpur", "India")
#fun_admit("Yash", 16, 1234567890, "Patna", "India")
#fun_admit("Ajay", 11, 45544454,"Karachi", "Pakistan")
#fun_admit("Tommy", 45, 2154125, "Tokyo", "Saudi")


a = str(input("Enter Name : "))
b = int(input("Enter Your Age : "))
c = int(input("Enter Phone Number : "))
d = str(input("Enter City : "))
e = str(input("Enter Country : "))
fun_admit(a, b, c, d, e)'''

# modules
# user define modules
'''
import mod
a = mod.car["Insurance"]
b = mod.car["Colour"]
c = mod.car["Model"]
d = mod.car["Brand"]
e = mod.car["Manufactured on "]
f = mod.car["Driven by"]

print(a,b,c,d,e,f)
'''


# predefined modules
'''
import platform

print("System :" , platform.system() )
print("Platform :" , platform.system() )
print("Processor :" , platform.processor() )
'''


# subprocess 
'''
import subprocess
subprocess.Popen('D:\Filmora9')'''


# imojis 
'''
import emojis

print(emojis.encode(":boat:"))
print(emojis.encode(":smiley:"))
'''
'''
import playsound
file = 'Alan Walker - Bgm'
playsound.playsound (file)
'''


# file handling in python  

# creating a file using python
'''
file = open('file.txt' ,'w')
file.write("My Name is Ayush")
file.close()
'''
'''
file = open('example.txt','r')
print(file.read())
'''


# class and object in python (oops)
'''
class person: 
    def __init__(self , name , age , city , job):
        self.name = name
        self.age = age
        self.city = city
        self.job = job
#addd = person("Ayush", 18, "Bhuj" , "Instructor")

a = str(input("Your Name : "))
b = int(input("Your Age : "))
c = str(input("Your City : "))
d = str(input("Your Job : "))

addd = person(a, b, c, d)

print("The name is : "+addd.name)
print("The Age is : " ,addd.age)
print("The city is : " +addd.city)
print("The Job Is : " +addd.job)
'''
