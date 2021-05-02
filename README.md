1. How to create a class, object, method and its signature
Ans. To create a class, use the keyword class:
    Example: class MyClass:
               x = 5

     Now we can use the class named MyClass to create objects:
    Example: p1 = MyClass()
             print(p1.x)

     A method is a function that “belongs to” an object:
       x.f()
    Example: xf = x.f
             while True:
                  print(xf())

2. Write a program to print your name.
Ans. person = input("KHALANDER RIHAN M")
       print(person)

3. Write a program for a Single line comment, multi-line and documentation comments
Ans. In Python, we use the hash symbol # to write a single-line comment.

4. Define variables for different Data Types int, Boolean, char, float, double and print on the Console.
Ans. Python allows you to assign a single value to several variables simultaneously. For example − a = b = c = 1. Here, an integer object is created with the value 1, and all three variables are assigned to the same memory location.
     In Python, boolean variables are defined by the True and False keywords
     To create a string, put the sequence of characters inside either single quotes, double quotes, or triple quotes and then assign it to a variable
     In python a float refers to a number that has decimal places.
     The Double Division operator in Python returns the floor value for both integer and floating-point arguments after division
     The print() function prints the specified message.

5. Define the local and Global variables with the same name and print both variables and understand the scope of the variables
Ans. The scope of global variables is the entire program whereas the scope   of local variable is limited to the function where it is defined.
     Example:  def f():
                   print(s)
               s = "I love Hyderabad!"
               f()

6. Write a function to print your name and call the function from main method.
       name = input("KHALANDER RIHAN M")
           print(name)
       if __name__ == '__main__'
