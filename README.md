for n in range(1, 101):  # Loop from 1 to 100 inclusive
    # Check if 'n' is divisible by both 3 and 5
    if n % 3 == 0 and n % 5 == 0:
        print("FizzBuzz")
    # If not divisible by both, check if 'n' is divisible by 3
    elif n % 3 == 0:
        print("Fizz")
    # Check if 'n' is divisible by 5
    elif n % 5 == 0:
        print("Buzz")
    # If 'n' is not divisible by either 3 or 5, print 'n'
    else:
        print(n)
