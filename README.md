# zeeshansami_fticonsulting
1. Detailed Steps to run the Library:
Step 1: Download the Library.
Step 2: Run Below Commands
python setup.py sdist
pip install .
Step 3: Open CMD in Directory
Step 4: Activate Virtual environment using below command:
.\myenv\Scripts\activate
Step 5: Type " python main.py"
Step 6: GUI will be Open.

2. Directory Structure for Testing:
Organize your package's directory in a standard format:
zeeshansami_fticonsulting/
|-- zeeshansami_fticonsulting/
|   |-- __init__.py
|   |-- visualization.py
|-- tests/
|   |-- __init__.py
|   |-- test_visualization.py
|-- README.md
|-- setup.py
|-- requirements.txt

1.	First, create the structure. You already have the visualizations.py file. Create a tests directory/folder in the same directory where visualizations.py is located.
2.	Inside the tests folder, create an empty file named __init__.py. This will make the tests directory recognizable as a package by Python.
3. Setting Up pytest:
Install pytest: pip install pytest
To run the tests, navigate to the root directory of your project and execute: pytest
