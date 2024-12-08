# Nonogram Solver

This repository contains a Python-based solution for solving Nonograms, including both rectangular and hexagonal grids. The solution uses SAT solvers to find valid configurations of colored cells according to the provided clues.

## Table of Contents
- Dependencies
- How to Run the Code
- Repository Structure
- Additional Information

## Dependencies
**Programming Language and Version**
- **Python:** Version 3.8 or higher.
**External Libraries**

The project requires the following external libraries:
- **PySAT:** A Python toolkit for prototyping with SAT solvers.

### Installing Dependencies

To install the necessary dependencies, you can use `pip`. Run the following command:

```bash
!pip install python-sat
```
This will install the python-sat package, which includes the necessary SAT solvers and tools to run the code.


## How to Run the Code

**1. Clone the Repository:** 

First, clone the repository to your local machine using the following command:
```bash
git clone <repository_url>

```
Replace `<repository_url>` with the actual URL of your repository.

**2. Navigate to the Project Directory:** 

Change to the directory containing the cloned repository:

```bash
cd <repository_folder>

```
**3. Prepare Your Input Files:**

Ensure that your `.clues` files (describing the nonograms) are placed in the `clues/ directory`   inside the repository. The `.clues` files should follow the specified format for rectangular and hexagonal grids.

**4. Run the Main Script:**
Execute the main Python script to solve the nonograms:

```bash
python <script_name>.py
```
Replace `<script_name>` with the name of your main Python file.


## Repository Structure

**Description of Key Components**

- **clues/**: Contains all the input .clues files required to describe the nonograms. Each file specifies a nonogram puzzle.
- **solutions/**: This directory will store the output files after the nonograms are solved. The files are named after the input files with additional suffixes indicating the approach used.
- **Assignment_1_3**: The main script that reads the `.clues` files, solves the nonograms using a SAT solver, and outputs the solutions.
- **README.md**: Documentation file explaining how to use the repository.

## Additional Information

**Supported Grid Types**
- **Rectangular Grids:** Standard nonogram grids with rows and columns.
- **Hexagonal Grids:** Nonogram grids arranged in a hexagonal pattern, with clues provided for horizontal, diagonal down-right, and diagonal down-left directions.

**Approaches Compared**

The code compares two different approaches to encoding and solving nonograms:

- **Basic Encoding:** A straightforward method of encoding the problem into SAT.
- **Alternative Encoding:** A potentially more compact or efficient method of encoding the nonogram into SAT.

**Efficiency Metrics**

For each nonogram, the solution process will output metrics such as:

- Time taken by each approach.
- Number of variables and clauses generated for the SAT solver.

**Extensibility**

The code is designed to be extensible. You can add new encoding approaches or modify the existing ones to test their efficiency.


## Contact
My mail: zahra.amanli@fau.de

My personal mail: zahra.amanli.za@gmail.com

My LinkedIn profile: www.linkedin.com/in/zahra-amanli 





