## Control FLow
Order in which lines of code are executed in a program.

eg.
print("Hello World")

a = 10
b = 5
result = a + b

print(f"The result of adding {a} and {b} is {result}")

print("Thank you")

# Sequential control flow
Execution of code statements one after another, in the order they appear in the program

# Conditional control flow / Control Flow
Execution of code statements based on some input

eg. 
if tomorrow is Saturday
    set alarm for 7
if tomorrow is Tuesday
    set alarm for 6

# Boolean Data Type Re-visit
Data type that has two values: True and False. Boolean values are used to control the flow of the program

eg.
is_the_earth_flat = False
print(is_the_earth_flat)

# Compariaon Operators / Relational Operators
Decide the relationship between the operands. Result of comparison is a boolean value (True/False)

eg.
if tomorrow == Saturday:
    set  alarm for 7
if tomorrow == Tuesday:
    set alarm for 6

# if, elif, else
Simplest form of AI (you could say that)
'if': checks the condition - if true, the intended blocks get executed - if false, it skips the intended blocks

eg.
today = "Tuesday"

if today == "Monday":
    print("Set an alarm for 5am!")
elif today == "Tuesday":
    print("Set an alarm for 6am!")
elif today == "Saturday":
    print("Set alarm for 7am!")

//
temperature = 30

if temperature  > 35:
    print("It's hit outside!")
elif temperature < 15:
    print("It's cold outside")
else:
    print("The weather is mild")

# pass
Does nothing... just passes... for now

# Boolean Operators
AND, OR, NOT. Operands need to be boolena as well

eg.
age = 20
has_permission = False

if age >= 18:
    if has_permission:
        print("ACCESS GRANTED")
    else:
        print("ACCESS DENIED")
else:
    print("ACCESS DENIED")

-> Can be reduced to this:

if  age >=18 and has_permission:
    print("ACCESS GRANTED")
else:
    print("ACCESS DENIED")

# Ternary Operator
Condense series of code to one line, where applicable

eg.
age = 20
has_permission = False

print("ACCESS GRANTED") if age >=18 and has_permission else print("ACCRESS DENIED")

// This:
temperature = 30

if temperature > 30:
    message = "It's hot"
else:
    message = "It's not hot"

print(message)

// To This:
temperature = 30

message = "It's hot" if temperature > 30 else "It's not hot"
print(message)

# Match-case
Control flow, similar to switch statement in other programming languages

eg.
day_number = 3

match day_number:
    case  1:
        day_name = "Monday"
    case 2:
        day_name = "Tuesday"
    case 3:
        day_name = "Wednesday"
    case 4:
        day_name = "Thursday"

print(day_name)