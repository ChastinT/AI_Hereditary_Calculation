# AI Hereditary Calculation

## Overview

AI Hereditary Calculation is a Python program designed to calculate the probabilities of genetic traits being passed down through generations within families. The program uses conditional probabilities and mutation rates to estimate the likelihood of individuals having specific genes and traits.

## How It Works

The program takes input data from a CSV file containing information about individuals' names, mothers, fathers, and known traits. It then computes the probabilities of different genetic scenarios based on the provided data, including the presence of one or two gene copies and the presence or absence of a particular trait.

## Usage

To use the program, follow these steps:

1. Ensure you have Python installed on your machine.
2. Clone the repository:

   ```bash
   git clone https://github.com/ChastinT/AI_Hereditary_Calculation.git
   cd AI_Hereditary_Calculation
3. Run the program with this command
    ```bash
    python heredity.py data.csv
  Replace data.csv with the path to your CSV file containing the family data.

## Input Format
The input CSV file should have the following fields:

**'name'**: Individual's name.

**'mother'**: Mother's name (if applicable).

**'father'**: Father's name (if applicable).

**'trait'**: Trait information (0 for no trait, 1 for trait, blank if unknown).

## Example
For an example input file and expected output, refer to the provided example.csv and example_output.txt files.

## Requirements
Python 3.x

## Acknowledgments
This program is based on probabilistic models and leverages the Python csv module for data loading. It is inspired by genetic inheritance principles and can be used for educational purposes in understanding hereditary calculations.
