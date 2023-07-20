# Modified Rankin Scale (mRS) Score Calculator

This repository contains a Python code for calculating the Modified Rankin Scale (mRS) score. The mRS is a widely used clinical assessment tool to measure the level disability or dependence in individuals who have suffered a stroke or other neurological conditions.

## Table of Contents
- [Introduction](#introduction)
- [Usage](#usage)
- [Understanding the Code](#understanding-the-code)
- [Examples](#examples)
- [Conclusion](#conclusion)

## Introduction
 Modified Rankin Scale (mRS) a scale that measures the degree of disability or dependence in individuals who have experienced a stroke or other neurological conditions. It is commonly used in clinical research and practice to assess the functional outcome of patients.

The mRS consists of seven levels, ranging from 0 to 6, each representing a different level of disability. The scale helps healthcare professionals and researchers evaluate the impact of a condition a patient's ability carry out daily activities and make informed decisions about their care.

## Usage
To use the mRS score calculator, follow these steps:

1. Clone the repository or download the `calculate_mrs_score.py` file2. Make sure you have Python installed on your system.
3. Open a terminal or command prompt and navigate to the directory where the `calculate_mrs_score.py` file is located.
4. Run the following command to execute the script:
   ```
   python calculate_mrs_score.py
   ```
5. Enter the disability level when prompted. The program will display the corresponding mRS score description.

## Understanding the Code
The `calculate_mrs_score` function takes a single parameter, `disability_level`, which represents the level disability on the Modified Rankin Scale. The function uses a series of conditional statements (`if`, `elif`, `else`) to map the provided `disability_level` to its corresponding mRS score description.

The function returns the mRS score description as a string. If the `disability_level` does not match any of the predefined levels, the function will return an appropriate error message.

## Examples
Here are some examples demonstrate how the code works:

```python
# Example 1
disability_level = 3
result = calculate_mrs_score(disability_level)
print(f"Modified Rankin Scale (mRS) Score: {result}")
```
Output:
```
Modified Rankin Scale (mRS) Score: Moderate disability, requiring some help but able to walk without assistance
```

```python
# Example 2
disability_level = 0
result = calculate_mrs_score(disability_level)
print(f"Modified Rankin Scale (mRS) Score: {result}")
```
Output:
```
Modified Rankin Scale (mRS) Score: symptoms at all
```

## Conclusion
The Modified Rankin Scale (mRS) score calculator provides a simple and efficient way to determine the level of disability or dependence in individuals who have experienced a stroke or other neurological conditions. By using this tool, healthcare professionals and researchers can assess the functional outcome of patients and make informed decisions about their care.

We hope this code and readme file have been helpful in understanding the mRS score calculation process. Feel free to use and modify the code according to your requirements. If you have any questions or suggestions, please don't hesitate to reach out.

🔗 **Keywords**: Modified Rankin Scale, mRS score, disability assessment, stroke, neurological conditions, clinical research, Python code
