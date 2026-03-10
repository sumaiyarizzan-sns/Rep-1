# hello_github.py

def greet(name):
    return f"Hello, {name}! Welcome to GitHub 🎉"

def add(a, b):
    return a + b

def multiply(a, b):  # ✅ New function added on a branch
    return a * b

if __name__ == "__main__":
    print(greet("World"))
    print(f"2 + 3 = {add(2, 3)}")
    print(f"2 x 3 = {multiply(2, 3)}")  # ✅ New line
