Download Link: https://assignmentchef.com/product/solved-cs2400-homework-4-count-violations
<br>
<strong>Objectives: </strong>

Use files, searching, and reference parameters.

A police department has a file of integers that represent driver license numbers for speeding violators. The department would like to know how many violations a particular license has.  Write a program that finds the number violations by counting the number of times a driver license number occurs in the data file.  The program should read the data file name and the driver license and determine the number of violations. Display an error message if the driver license is invalid (i.e. negative) or the file does not exist.

The number of violations is equivalent to the number of occurrences that particular license appears in the file. If the license has more than 6 violations, print a message indicating that the license should be suspended.

<strong>Your program must include the following two functions: </strong>

<ul>

 <li>A function that takes an input stream, a license number, and returns the number of violations. It should return 0 if the license is not found.</li>

 <li>A function that prints the results.</li>

</ul>

o License number and the number of violations o Whether the license needs to be suspended or not

<strong>Sample interaction: </strong>

./a.out Enter the data file name: violations.txt

Enter a license number: 999

Driver license 999 has 0 violations.

./a.out Enter the data file name: violations.txt

Enter a license number: 22222

Driver license 22222 has 9 violations.

Driver license 22222 should be suspended ./a.out Enter the data file name: violations123.txt Error: File name violations123.txt does not exist ./a.out Enter the data file name: violations.txt

<h1>Enter a license number: -999 Error: invalid license number</h1>

<strong>             </strong>