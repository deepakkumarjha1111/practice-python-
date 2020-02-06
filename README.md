#  practice-python-
#  Python codes


>>print("welcome")

#1)								#op- 1
"""names1 = ['Amir', 'Bala', 'Chales']
 
if 'Bala' in names1:
    print(1)
else:
    print(2)"""

#2)
'''a=10
b=20
def change():
    global b
    a=45
    b=56
change()
print(a)
print(b)'''

#3)								#op=0
'''i=0
def change(i):
   i=i+1
   return i
change(1)
print(i)'''

#4)       							#op=6 15
'''def sum(*args):                 
   """Function returns the sum 
   of all values"""
   r = 0
   for i in args:
      r += i
   return r
print( sum.__doc__)
print(sum(1, 2, 3))
print( sum(1, 2, 3, 4, 5))'''
#5)
'''x = 2                           #op=3 4
for i in range(x):          #range(2)=>0,1
    x += 1                       #x=x+1 not x=x+i
    print (x)'''                   
#)6
'''for i in [1, 2, 3, 4][::-1]:              #op=4321
    print (i)'''
 #7)								#same pr 0 diff pr 1
"""print(4^12)
print(0^1)# i.e one"""

#8)						op- my,name,is,x
'''string = "my name is x"
for i in string.split():
    print (i, end=", ")'''
#9)                                #op-08
     								#		  0
     								#		  8
#x = (i for i in range(3))<-- iska matlab hai x=[0,1,2] but not three included


#i)
'''x=[0,8]
for i in x:
    print(i,end='')
print()
for i in x:
    print(i)'''
    
    
# ii)
"""x = (i for i in range(3))
for i in x:
    print(i)
for i in x:
    print(i)"""
#10)									#op- 0,1,2,3,4
"""for i in range(10):
    if i == 5:
        break
    else:
        print(i)
else:
    print("Here")"""
#ii) 							
  						     	#welcome
									  #0
									  #1
									#  2
								#	  3
								#	  4
								#	  6
									#  7
								#	  8
									 # 9
								#	  here
"""for i in range(10):
    if i == 5:
        continue
    else:
        print(i)
else:
    print("Here")"""

#11)				#op- gives address of var. a
'''a=10
print(id(a))   '''

#12)								#op-abcd12
"""L = ['a','b','c','d','12'] 
print ("".join(L))"""
 
 #13)
"""print(type(type(type))) 	#op-class 'type'
print(type(int))				#op class 'type'
print(type(type(int)))      #op- class 'type'
"""
#14)									op-117
#print(0x35 | 0x75)        

#####DOGHT####

#15)													#op->15
			#similarly inoctal and hexa decimal
#To find the decimal value of 1111, that is 15, we can use the function:
"""print(int('1111',2))
print(int('1111',8))
print(int('1111',16))"""

#16)        #op=6
"""y=2
def foo():
    return total + 1+y
total = 3
print(foo())
"""
#17)           			op= _b is private only
"""def Demo:
def __init__(self):
    __a = 1
    self.__b = 1
    self.__c__ = 1
    __d__= 1"""
#18)						                 	#op=30
								##DOUGHT##
"""class A:
    def __init__(self):
        self.multiply(15)
        print(self.i)
 
    def multiply(self, i):
        self.i = 4 * i;
class B(A):
    def __init__(self):
        super().__init__()
 
    def multiply(self, i):
        self.i = 2 * i;
obj = B()"""

#19)						###DOUGHT##
"""class Demo:
    def __init__(self):
        self.x = 1
    def change(self):
        self.x = 10
class Demo_derived(Demo):
    def change(self):
        self.x=self.x+1
        return self.x
def main():
    obj = Demo_derived()
    print(obj.change())"""
#20)								##DOUGHT##
"""class A:
    def __init__(self, x= 1):
        self.x = x
class der(A):
    def __init__(self,y = 2):
        super().__init__()
        self.y = y
def main():
    obj = der()
    print(obj.x, obj.y)
main()"""

#21)
##Suppose B is a subclass of A, to invoke the __init__ method in A from B, what is the line of code you should write?
#answer-->>      A.__init__(self)

#22)								#op=  A disp()
#here (pass ) is simply passing the controll to the further prog execution .....is same as an empty class in C or C++ with curly braces


"""class A():
    def disp(self):
        print("A disp()")
class B(A):
    pass
obj = B()
obj.disp()"""

#23)                        # op= __main__
								#DOUGHT##
"""class Demo:
    def __init__(self):
        pass
 
    def test(self):
        print(__name__)
 
obj = Demo()
obj.test()"""


#24)								#op= Old
						
"""class test:
    def __init__(self):
        self.variable = 'Old'
        self.Change(self.variable)
    def Change(self, var):
        var = 'New'
obj=test()
print(obj.variable)"""

#25) 								#op= 7
"""class change:
    def __init__(self, x, y, z):
        self.a = x + y + z
 
x = change(1,2,3)
y = getattr(x, 'a')
setattr(x, 'a', y+1)
print(x.a)"""

#26)								# op- Hello World
"""class test:
     def __init__(self,a="Hello World"):
         self.a=a
 
     def display(self):
         print(self.a)
obj=test()
obj.display()"""
#27)
#What is unpickling?
#ans::It is used for object deserialization

#28)
#-seek()--> sets the file current postion
#-tell()--> tells about the curennt postion
#- read()---> to read the file content

#29)
"""attributes::-
rename
closed
mode
"""
 #30)
"""f = None
for i in range (5):
    with open("data.txt", "w") as f:
        if i > 2:
            print("g")
print(f.closed)"""


 

 
print("thanks for good executing")

