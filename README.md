# CAP5625 - Programming Assignment 3 README

## Overview

This README provides instructions on how to run the provided program for Programming Assignment 2, Algorithm 1 (vectorized). This assignment focuses on implementing a penalized (regularized) least squares fit of a linear model using elastic net, with the model parameters obtained by coordinate descent. The tuning parameter will be chosen using five-fold cross validation, and the best-fit model parameters will be inferred on the training dataset conditional on an optimal tuning parameter..

## Prerequisites

Before running the program, ensure you have the following prerequisites:

1. MATLAB installed on your computer. While MATLAB Online is an option, please note that the MATLAB Drive storage provided may not be sufficient to run this program efficiently. Additionally, you can access MATLAB for free through your FAU account.

2. The provided dataset file named "Credit_N400_p9.csv" should be available in the same directory as the MATLAB script.

## Running the Program

Follow these steps to run the program:

1. Open MATLAB on your computer.

2. Navigate to the directory containing the MATLAB script and the dataset file.

3. Open the MATLAB script (the file containing your program).

4. Run the script by clicking the "Run" button in the MATLAB Editor or by entering `run script_name.m` in the MATLAB command window, where `script_name.m` is the name of your script.

   For example: `run source_code.m`

6. The program will execute, performing Elastic Net, Five-Fold Cross-Validation, and retraining the model with the optimal parameters.

7. Once the program completes, it will not display the estimated model parameters `betahat` in the MATLAB console. However, these results are provided as .png deliverables

## Additional Notes

- Ensure that the dataset file "Credit_N400_p9.csv" is correctly formatted and contains the required data columns for the program to execute successfully.

- Make sure to have adequate computing resources, especially if you increase the number of iterations or use a large dataset, as training may take longer on slower hardware.

- This README assumes that you have a basic understanding of MATLAB. If you encounter any issues or have questions, refer to the MATLAB documentation.

Happy coding ;)
