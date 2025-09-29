# ACCCA---Mendoza-Clarence-Tomas-PA2
This repository is for use of academics purposes and are needed. This is also for PA2 with numpy as focus in the problems.


## DESCRIPTIONS ABOUT THE ORDER OF CODES USED:

#### First code: NORMALIZATION PROBLEM:
Create a 5x5 array with random values stored in it. Then; follow the process of centering which means subtracting the data from the
mean and scaling means dividing with its standard deviation. This formula is what is used for the normalized values in the code.

#### Second code: DIVISIBLE BY 3 PROBLEM:
Create a 10x10 array ranging from 1-100 with their values squared. From this ndarray, determine all the elements that are divisible by 3. Save the result as div_by_3.npy


## DESCRIPTION OF FUNCTIONS USED IN MY CODE:

#### NORMALIZATION PROBLEM:
```
"X = np.random.rand (5, 5)" - Creates a 5x5 array with random values stored.
"mean = X.mean()" - A simple use of the mean function already included in Python. This automatically gets the mean for use in the formula.
"standard = X.std()" - Like the mean function, this automatically gets the standard deviation of the value that is then used for the formula.
"normalized = (X - mean) / standard" - Formula used.
"np.save("X_normalized.npy", normalized)" - This creates a file that may be used in later dates for normalization related problems.
```

#### DIVISIBLE BY 3 PROBLEM:
```
"numbers = np.arange (1, 101) ** 2" = This creates an array with numbers ranging from 1-100, this is automatically a 1 row array as the shape is not specified.
"array = numbers.reshape (10, 10)" - Reshapes the array created earlier to be 10x10.
"modulo = array[array % 3 == 0]" - Uses the modulo function to get all the numbers divided by 3 and that of without remainders. Uses a type of Boolean slicing.
"np.save("div_by_3.npy", modulo)" - This creates a file that may be used in later dates for modulo problems.
```

## HOW TO USE THE CODE:
For this set of codes, input is actually not required and is only to be ran. No need to change the code unless want to remove the print code lines.

Note: These descriptions are all copied from the instructions in PA2 assignment in ACCA UST.
