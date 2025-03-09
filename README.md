## PiXELL River Transaction Report

I will be using the VSCode built-in debugger to ensure full functionality of the PiXELL River Transaction Report program.

## Code Modification [1]

Added error handling when the data file cannot be found in the program directory.

## Code Modification [2]

Added validation for transaction types and amounts. Invalid transaction types/amounts are now appended to a list along with 
their corresponding transaction.

## Code Modification [3]

Changed indentation, moved around some variables, changed invalid variable names, and added a proper increment for transaction_counter to prevent the Dividebyzero error. All of this was to ensure that records would be read through and processed properly.