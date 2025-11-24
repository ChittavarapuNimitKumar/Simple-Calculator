Simple Calculator Project

Aim:
To create a simple command-line calculator program that performs basic arithmetic operations such as addition, subtraction, multiplication, and division to introduce programming problem solving.

Software Required:
Python 3.x interpreter
Any code editor or IDE (e.g., VS Code, PyCharm)

Algorithm
1.Display a menu of operations to the user.
2.Take user input for the choice of operation.
3.Take two numerical inputs from the user.
4.Perform the selected operation based on the choice.
5.Display the result, handling possible errors (e.g., division by zero)

Code:
def sum(x,y):
    return x+y
def sub(x,y):
    return x-y
def mul(x,y):
    return x*y
def divide(x,y):
    if y==0:
        return "Division by zero not possible"
    return x/y
print("Welcome to calculator program (for 2 numbers only)")
while True:
    print("Enter 1 to add")
    print("Enter 2 to Subtract")
    print("Enter 3 to multiply")
    print("Enter 4 to divide")
    print("Enter 5 to exit from the calculator")
    choice=int(input("Enter your choice = "))
    if (choice==5):
        break
    num1=int(input("Enter first number "))
    num2=int(input("Enter second number "))
    if (choice==1):
        print("Result : ",sum(num1,num2))
    elif(choice==2):
        print("Result : ",sub(num1,num2))
    elif (choice==3):
        print("Result : ",mul(num1,num2))
    elif (choice==4):
        print("Result : ",divide(num1,num2))
    
    else:
        print("Enter a Valid Input")


Sample Input and Output:
Example 1:
Enter choice (1/2/3/4): 1
Enter first number: 10
Enter second number: 5
Result: 15.0

Example 2:
Enter choice (1/2/3/4): 4
Enter first number: 10
Enter second number: 0
Result: Error: Division by zero

Conclusion:This project helps beginners grasp basic programming ideas like conditional statements, functions, and user input handling. It also allows them to practice fundamental problem-solving skills.
