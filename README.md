# Assignment: BMI Calculator (Python)

## Overview
In this assignment, you will build a Python program that calculates a user's Body Mass Index (BMI) from weight and height. This task practices user input, numeric calculations, and conditional logic.

## Requirements
Your program must:

- Read two numbers from input:
  - weight in kilograms
  - height in meters
- Calculate BMI using this formula:
  - `BMI = weight / (height * height)`
- Print the BMI rounded to one decimal place.
- Print the BMI category exactly as one of the following:
  - `Underweight`
  - `Normal weight`
  - `Overweight`
  - `Obese`

Use these category rules:

- BMI less than `18.5` -> `Underweight`
- BMI from `18.5` to `24.9` -> `Normal weight`
- BMI from `25.0` to `29.9` -> `Overweight`
- BMI `30.0` or higher -> `Obese`

## Input
Two lines:

1. A decimal number for weight in kilograms
2. A decimal number for height in meters

## Output
Two lines:

1. `BMI: <value>`
2. One category line exactly as:
   - `Underweight`
   - `Normal weight`
   - `Overweight`
   - `Obese`

## Examples

**Input**
```text
70
1.75
```

**Output**
```text
BMI: 22.9
Normal weight
```

**Input**
```text
95
1.80
```

**Output**
```text
BMI: 29.3
Overweight
```

## Starter File
Create a file named `main.py` that reads input using `input()` and prints the result using `print()`.

## Evaluation Criteria (Rubric)
- 40%: Correct BMI calculation
- 30%: Correct BMI category logic
- 20%: Exact output format
- 10%: Clear and readable code

## Suggested Autograding Tests
- `70`, `1.75` -> `BMI: 22.9` and `Normal weight`
- `50`, `1.70` -> `BMI: 17.3` and `Underweight`
- `80`, `1.75` -> `BMI: 26.1` and `Overweight`
- `110`, `1.80` -> `BMI: 34.0` and `Obese`
- Boundary case: `72.03`, `1.70` -> `BMI: 24.9` and `Normal weight`
- Boundary case: `72.25`, `1.70` -> `BMI: 25.0` and `Overweight`

## Task ID
Task ID: TASK-2
