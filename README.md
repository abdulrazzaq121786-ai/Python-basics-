# Python-basics-
# 1. Print statement
print("Hello World")

# 2. Variables
name = "Abdul"
age = 20
print(name)
print(age)

# 3. Data types
a = 10        # int
b = 2.5       # float
c = "Python"  # string
d = True      # boolean
print(a, b, c, d)

# 4. Input from user
user_name = input("Enter your name: ")
print("Hello", user_name)

# 5. Type conversion
user_age = int(input("Enter your age: "))
print(user_age + 1)

# 6. Arithmetic operators
x = 10
y = 3
print(x + y)
print(x - y)
print(x * y)
print(x / y)
print(x % y)

# 7. Comparison operators
print(x > y)
print(x < y)
print(x == y)
print(x != y)

# 8. Logical operators
p = True
q = False
print(p and q)
print(p or q)
print(not p)

# 9. If condition
age = 18
if age >= 18:
    print("Adult")

# 10. If-else
age = 16
if age >= 18:
    print("Adult")
else:
    print("Minor")

# 11. If-elif-else
marks = 75
if marks >= 90:
    print("A Grade")
elif marks >= 60:
    print("B Grade")
else:
    print("Fail")

# 12. While loop
i = 1
while i <= 5:
    print(i)
    i += 1

# 13. For loop
for i in range(1, 6):
    print(i)

# 14. String indexing
text = "Python"
print(text[0])
print(text[-1])

# 15. String slicing
sentence = "Python Programming"
print(sentence[0:6])
print(sentence[7:])

# 16. String methods
msg = "hello world"
print(msg.upper())
print(msg.lower())
print(msg.title())

# 17. String concatenation
a = "Hello"
b = "Python"
print(a + " " + b)

# 18. f-Strings
name = "Abdul"
age = 20
print(f"My name is {name} and my age is {age}")
