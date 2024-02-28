# Leaves Detection - Machine Vision

This repository contains all relevant Jupyter notebooks, documentation for the mid term exam project.

## Prerequisites
1. [Python 3.11.3](https://www.python.org/downloads/release/python-3113/)

## Starting the project
1. Install virtual environment:

```bash
pip install virtualenv
```
2. Create virtual environment:
```bash
python -m venv venv
```
3. Activate the virtual environment by running the following command in cmd/terminal:
```bash
"venv/Scripts/activate"
```
4. Run the following command in cmd/terminal in order to install the proper requirements and dependencies for the project:
```bash
pip install -r "requirements.txt"
```
5. Run the following command in cmd/terminal in order to open jupyter lab project, there you can checkout all the approaches for this exam:
```bash
jupyter lab
```
6. I have selected two approaches that I see fit. You can run those with the following command in cmd to check whether the solution works:
```bash
python hough_solution.py
```
You enter the folder path that you want to test the solution with and in the folder hough_transform_results_solution you can see the drawn images and in cmd the results of every image will be printed as well.
```bash
python find_contours_solution.py
```
You just have to enter the folder with the images you want to test on the solution, and for each picture to enter a correct number of leaves, as a return you'll get for which image is correct or not, and the accuracy of this solution at the end.

7. After this, you can run the project. When you are done, deactivate the virtual environment by running the following command in cmd/terminal:
```bash
deactivate
```