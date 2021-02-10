# Enough Python/Flask to TA for C15 Workshop, AdieCon 2021

## Python Installation and Python 3

## Python Syntax Crash Course: Fizzbuzz

```python
def fizzbuzz(num):
    if num % 3 == 0 and num % 5 == 0:
        return "Fizzbuzz"
    elif num % 3 == 0:
        return "Fizz"
    elif num % 5 == 0:
        return "Buzz"
    else:
        return num

print("Python supports comma-separated print args", "and it's pretty useful!")

print(f"To interpolate, Python 3 introduced the f-string syntax. The f before the string lets us print expressions: {fizzbuzz(1)}")

print("3 should give Fizz:", fizzbuzz(3))
print("5 should give Buzz:", fizzbuzz(5))
print("15 should give Fizzbuzz:", fizzbuzz(15))
print("Everything else should give back the number:", fizzbuzz(98))

# Run this with $ python3 fizzbuzz.py

```

## OOP in Python: `self`



## Testing in Python: pytest

## Preview of Learn

## Flask Tooling

## Returning JSON in Flask

## Feedback