# cool-beans
def sphere(a):
    return 4*3.14*(a*a)
result = sphere(2)
print ("spheres area is:",result)
#------------------------------------
def changechecker(num):
    if num%5==0:
        print ("no pennies needed")
    else:
        print ("pennies needed")
changechecker(25)
changechecker(17)
#------------------------------------
def PrimeNumber(num):
    prime = True #set up a variable to True
    for i in range(2, num): #have a for loop here
        if num % i ==0:
            prime = False #set variable False
   
    return prime #return variable name
prime = PrimeNumber(17)
if prime == True:
    print("it is a prime number")
    
else:
    print("it is not a prime number")
    
PrimeNumber(18)
