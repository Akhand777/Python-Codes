# Python-Codes
this is python new module 

#comment:-
    
    > Comment in python are identified with hash(#) symbol.
    > Hash characters in a string are not considered comments, however, > There are three ways to write a comment - 
        as a separate line, 
        beside the corresponding statement of code, or 
        as a multi-line comment block

    > Python has only single line comment system.
    > a comment ignored by interpreter(in short conversion of character 
        #to binary is not possible)
    > for multiline comment we use """ comment """ triple cod


#Variables:-
    --> Variables are containers for storing data values.

    ->A Python variable is a symbolic name that is a reference or
    pointer to an object. 
    ->Once an object is assigned to a variable, you can refer to the object by that name. But the data itself is still contained within the object.

    > Rule1 : A variable never start with a number 
    > Rule2 : A variable never contain special character except "_".
    > Rule3 : A variable must be readable.
    > Rule4 : Variable names are case-sensitive (age, Age and AGE are three different variables)

Data type:-
    1. integer --> int-- > integer contain 0-9 values only.
    2. float --> a value which hold 0-9 and decimal symbole in it called floating point number or float
    3. String --> str  
    4. List --> list
    5. Tuple --> tuple
    6. Set  --> set
    7. dictionary --> dict
    8. frozenset --> 
    9. boolean --> bool
    10. complex 

Example	Data Type:-

    x =     "Hello World"	                                =   str	
    x =     20	                                            =   int	
    x =     20.5	                                        =   float	
    x =     1j	                                            =   complex	
    x =     ["apple", "banana", "cherry"]	                =   list	
    x =     ("apple", "banana", "cherry")	                =   tuple	
    x =     range(6)	                                    =   range	
    x =     {"name" : "John", "age" : 36}                   =	dict	
    x =     {"apple", "banana", "cherry"}                   =	set	
    x =     frozenset({"apple", "banana", "cherry"})	    =   frozenset	
    x =     True	                                        =   bool	
    x =     b"Hello"	                                    =   bytes	
    x =     bytearray(5)                                    =	bytearray	
    x =     memoryview(bytes(5))	                        =   memoryview	
    x =     None	                                        =   NoneType


#Numbers:-

There are three numeric types in Python:
        ->int
        ->float
        ->complex     #Note: You cannot convert complex numbers into another number type.

    ->integer(int):-
        Int, or integer, is a whole number, positive or negative, without decimals, of unlimited length.

        example-> a=10
                  b=2594541148484 or b=-2594541148484

    ->float:-
        Float, or "floating point number" is a number, positive or negative, containing one or more decimals.

        example-> a=20.545
                  b=3.4e2 or b=-3.4

    ->complex:-
        Complex numbers are written with a "j" as the imaginary part.

        example-> a=2j+5
                  b=3j or b=-3j