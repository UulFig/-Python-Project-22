# -Python-Project-22
#22 Calculator (Base * Height ) / size

def calculator():
    height = float(input("What's the height of the wall?\n"))
    width = float(input("What's the width of the wall?\n"))
    coverage = float(input("What's the coverage for each can?\n"))

    calc = (height * width) / coverage

    print(f"The total needed is: {round(calc)} cans")

calculator()

