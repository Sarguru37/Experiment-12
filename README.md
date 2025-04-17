### Name : SARGURU K
### Reg No : 212222231034
# Experiment-12
## Pytest Python program for Addition
# Aim:
To write a python program for addition of two numbers and test the test cases using Pytest. 
# Algorithm: 
Step 1: Write the python program for addition of two numbers. 

Step 2: Make sure that function name should be “def test_*():” and the line to be tested 
should have assert keyword at the beginning. 

Step 3: Write some test cases for to be tested and save it as “test_add.py”. 

Step 4: Open command prompt and change the directory to where pytest and program is 
saved and type “pytest  test_add.py” and run it. 

Step 5: Stop the program. 
# Program:
```python
def add(a,b): 
    return a+b 
def test_3_plus_5_equals_8(): 
    assert add(3,5) == 8 
def test_2_plus_3_equals_5(): 
    assert add(2,3) == 6 
```
# Output
![Screenshot 2025-03-29 105935](https://github.com/user-attachments/assets/7d248eef-b2aa-4c40-9988-8d6291576b2c)

# Result

Thus, the python program for addition is tested using pytest and executed and output is 
verified successfully.
