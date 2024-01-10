# Overview

This brief guideline is designed to simplify the use of the Python script developed for generating license plate imagery data, essential for training machine learning-based ALPR algorithms.

# Installation

A target folder shall be created as the central location for all files related to the project. All relevant files, residing in their respective subfolders, should be transferred to the target folder. The content of the various directories is as illustrated below and detailed in Table 1 below.

**Directory Tree:**

| File     | Description |
| ------ | ----------- |
| xxx    | Script to generate the synthetic data as described in Section \ref{sec:datagen}. |
| ...    | ... |
| (31)   | This file. |

# Creation Of Synthetic Data / License Plate Generator

## Dependencies

The following modules shall be installed and made available to the environment.

**Table 2: List Of Dependencies For Data Generator**

| Package Name | Version Number |
| ------------ | -------------- |
| Pillow       | 9.5.0          |
| ...          | ...            |

## Configuration Parameters To Be Set

The following parameters shall be defined and set before execution of the script.

**Table 3: List And Meaning Of Configuration Parameters**

| Parameter                     | Type  | Example | Description |
| ----------------------------- | ----- | ------- | ----------- |
| number_of_plates_to_generate  | Int   | 1000    | Number of plates to be generated in total |
| ...                           | ...   | ...     | ...         |

## Execution


## Output

The output of the script will include:

1. **Imagery Data:** A set of JPG-Files...
2. **Mapping File:** An Excel file...
3. **Statistical Descriptions:** A set of PNG-Files...
