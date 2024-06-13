# Fibonacci_sequence
#A python program to find the fibonacci number at the number that was entered by user
def fib1(num):
    if num <= 2:
        return 1
    else:
        return fib1(num - 1) + fib1(num - 2)
    
number = int(input("Enter a number to find the fibonacci sequence: "))

print("Fibonacci number is "+str(fib1(number)))
