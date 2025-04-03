# basic-code-for-python
This repository contains a collection of Jupyter Notebooks designed to help with Python programming practice. It includes fundamental concepts, list and dictionary operations, and various coding problems for hands-on learning.

📂 Contents
BASIC.ipynb

Covers fundamental Python concepts like input/output, data types, and arithmetic operations.

Example:

python
Copy
Edit
a = int(input('Enter a number 1'))
b = float(input('Enter a number 2 in float'))
sum = a + b
print(sum)
print(type(sum))
Practice.ipynb

Includes coding exercises such as solving polynomial equations, reversing lists, and checking Armstrong numbers.

Example:

python
Copy
Edit
import cmath
def quadratic_roots(a, b, c):
    d = (b**2) - (4*a*c)
    root1 = (-b + cmath.sqrt(d)) / (2*a)
    root2 = (-b - cmath.sqrt(d)) / (2*a)
    return root1, root2
list.ipynb

Focuses on list operations: accessing, updating, appending, concatenation, and repetition.

Example:

python
Copy
Edit
a = [10, 20, 30, 40, 50]
print(a[3])  # Accessing elements
a.append(60)  # Adding an element
print(a)
dict.ipynb

Demonstrates dictionary operations: accessing, modifying, and using dictionary functions.

Example:

python
Copy
Edit
thisdict = {
    "brand": "Ford",
    "model": "Mustang",
    "year": 1964
}
print(thisdict["model"])  # Accessing dictionary values
some question.ipynb

Contains a variety of small coding problems for practice, including swapping numbers, checking even/odd, and basic arithmetic.

Example:

python
Copy
Edit
a, b = 5, 10
a, b = b, a  # Swapping without a temp variable
print("Swapped numbers:", a, b)
🚀 How to Use
Clone this repository:

bash
Copy
Edit
git clone https://github.com/your-username/your-repo.git
cd your-repo
Install Jupyter Notebook if you haven’t already:

nginx
Copy
Edit
pip install notebook
Run Jupyter Notebook:

nginx
Copy
Edit
jupyter notebook
Open any of the .ipynb files to start practicing.

