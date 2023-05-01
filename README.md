# variables_n_python
In Python, a variables is a name that store a data.
Syntax: 
variable_name = Value
i -	Creating variables: 
We can assign a value to variable by using the sign “=”. Example,
a=’3’ #create a variable x and assigned it the value 3 as string type.
b= 3 #create a variable x and assigned it the value 3 as integer type.
c =3.0 #create a variable x and assigned it the value 3 as float type.
We can use the following functions allow to define a type of variable using the str(), int() or float() methods. Example, 
x= str(3) # use str() method to define a string
y =int(3) # use int() method to define a integer
z = float(3) #use float() method to define a float
ii -	Multiples variables:
In Python, we permit to assign multiple variables in one line. Example,  
x , y, z = “hatim”, “maha”, “zakaria” 
Also, we can assigne multiple variables a one value in one line. Example, 
x = y = z = “hatim”
We can extracte the values from list or tuples into variables, its called unpacking. Example, 
countries = [“algeria”, ‘’France’’, “morocco”]
x, y, z = countries #unpacking values in list to variables x,y,z  
We can print the output variables using print() function. Example,
countries = [“algeria”, ‘’France’’, “morocco”]
x, y, z = countries
print(x)
