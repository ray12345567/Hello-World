# Hello-World
An example code for a while loop 
def number():
    addition = 0
    while True:
        num = int(input("Enter a number: "))
        if num % 2 == 0:
            print("The number is even, loop will break")
            break
        addition += num
        print("The sum of all entered numbers is", addition)

