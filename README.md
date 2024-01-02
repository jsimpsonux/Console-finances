# Console-finances
JavaScript console finance challenge

## Description

Using for loops and accessing a large array then making calculations for a finance log to compare data.

## Table of Contents

N/A

## Installation

N/A

## Usage

Users can see calculations that were made using for loops and accessing an array.

Launch the index.html and right-click on browser then select 'Inspect' the navigate to 'console' to see results.

## Pseudocode

```
<--- Calculates the number of months --->

console.log("Total months:" ARRAY.length)


<--- Calculates the total of numbers in array --->

FirstVARIABLE = STORAGE;

FOR (INCREMENT IS 0; INCREMENT LESS ARRAY.length; INCREMENT++) {
StorageforTotal ADD & EQUAL ARRAY[INCREMENT][ACCESS first column];
}

console.log("Total:" + CONCATENATION + "$")


<--- Calculates the Average change --->

FirstVARIABLE = STORAGE;

FOR (INCREMENT IS 0; INCREMENT LESS ARRAY.length MINUS; INCREMENT++) {
FirstVARIABLE ADD & EQUAL ARRAY[INCREMENT ADD ONE][ACCESS second column] MINUS ARRAY[INCREMENT][ACCESS second column];
}

SecondVARIABLE IS FirstVARIABLE DIVIDED (ARRAY.length MINUS 1);

console.log("Average change:" + CONCATENATION + SecondVARIABLE)


<--- Calculates the Greatest Increase and Decrease --->

MaxVARIABLE IS STORAGE;
MinVARIABLE IS STORAGE;
MonthVARIABLE;

FOR (INCREMENT IS 0; INCREMENT LESS ARRAY.length MINUS 1; INCREMENT++) {

DifferenceVARIABLE IS ARRAY.length[INCREMENT PLUS 1][ACCESS first column] MINUS ARRAY[INCREMENT][ACCESS first column];

IF (DifferenceVARIABLE GREATER MaxVARIABLE) {
 MaxVARIABLE EQUALS DifferenceVARIABLE;
 MonthVARIABLE EQUALS ARRAY[INCREMENT PLUS 1][ACCESS first column]
}

IF (DifferenceVARIABLE LESS MinVARIABLE) {
 MinVARIABLE EQUALS DifferenceVARIABLE;
 MonthVARIABLE EQUALS ARRAY[INCREMENT PLUS 1][ACCESS first column]
}

}

console.log("Greatest Increase in Profits/Losses:" + CONCATENATION + MaxVARIABLE)
console.log("Greatest Decrease in Profits/Losses:" + CONCATENATION + MinVARIABLE)

```
## Features

JavaScript

HTML

Console