# COMP1844 - Information Analysis and Visualisation

## Laboratory Session 1: Python Fundamentals

### Overview

This laboratory session introduces fundamental Python programming concepts essential for data analysis and visualization. Students will familiarize themselves with development environments (PyCharm/Jupyter Notebook) and practice basic programming constructs.

### Learning Objectives

By the end of this session, you will be able to:

- Set up and use PyCharm or Jupyter Notebook environments
- Define and implement Python functions
- Handle errors using conditional statements and exception handling
- Solve mathematical problems using Python

### Project Structure

```
UoG-COMP1844-SP26-Lab01/
│
├── data/                     # Data files
│
├── notebooks/                # Jupyter notebooks
│
├── src/                      # Source code
│
├── output/                   # Output files and results
│
├── requirements.txt          # Python dependencies
├── README.md                 # Project documentation
└── LaboratorySession1.pdf    # Lab instructions
```

### Lab Tasks

#### Task 1: Environment Familiarisation

Get comfortable with PyCharm or Jupyter Notebook by running basic commands:

    print('Hello World')
    a = 10
    b = 5
    print(a, '+', b, '=', a+b)

#### Task 2: Arithmetic Functions

Define and test 4 functions for basic arithmetic operations:

- Addition
- Subtraction
- Multiplication
- Division (with error handling)

2.1 Use if statement to avoid division by zero

2.2 Use exception handling with try-except:

    try:
        c = a / b
        print(c)
    except ZeroDivisionError:
        print('Division by zero')

#### Task 3: Quadratic Equation Solver

Solve quadratic equations of the form: $ax^2 + bx + c = 0$

Using the quadratic formula: $x = \dfrac{-b +/- \sqrt(b^2-4ac)}{2a}$

Sub-tasks:

- 3.1 Write a script to calculate solutions for real numbers
- 3.2 Handle case when discriminant equals zero (one solution)
- 3.3 Handle negative discriminant (no real solutions)
- 3.4 Handle case when a = 0 (not a quadratic equation)
- 3.5 Implement combined error handling with single IF statement

### Installation and Setup

1. Clone the repository

   git clone [repository-url]
   cd UoG-COMP1844-SP26-Lab01
2. Create a virtual environment (recommended)

   python -m venv venv
   source venv/bin/activate
3. Install dependencies

   pip install -r requirements.txt
4. Launch Jupyter Notebook (optional)

   jupyter notebook

### Dependencies

See requirements.txt for a complete list of required libraries. Key packages include:

- numpy - Numerical computing and mathematical operations
- pandas - Data manipulation and analysis
- matplotlib - Data visualization
- jupyter - Interactive notebook environment

### Resources

- Python Documentation: https://docs.python.org/3/
- NumPy Documentation: https://numpy.org/doc/
- Matplotlib Documentation: https://matplotlib.org/stable/contents.html
- Jupyter Notebook Documentation: https://jupyter-notebook.readthedocs.io/

### License

This project is part of the COMP1844 module at the University of Greenwich.

Laboratory Session 1 - Spring 2026
