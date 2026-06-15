name = input("What is your name? ")
age = int(input("What is your age? "))

if age >= 18:
    print(f"{name}, you are eligible to vote (Age: {age}).")
else:
    print(f"{name}, you are not eligible to vote (Age: {age}).")
