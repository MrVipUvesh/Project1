# Interactive Personal Data Collector

A simple beginner-friendly Python program that collects some basic information from the user and displays it in a clean format.

This project is mainly made to practice Python fundamentals such as `input()`, data types, type conversion, f-strings, `id()`, and basic calculations.

## What This Program Does

The program asks the user for:

- Name
- Age
- Height in meters
- Favourite number

After collecting the information, it displays:

- The entered value
- Its Python data type
- Its memory address using `id()`
- An approximate birth year calculated from the entered age

## Example

```text
Welcome to the Interactive Personal Data Collector!

Please enter your name: Uvesh
Please enter your age: 18
Please enter your height in meters: 1.75
Please enter your favourite number: 7

Thank you! Here is the information we collected:

Name: Uvesh (Type: <class 'str'>, Memory Address: 123456789)
Age: 18 (Type: <class 'int'>, Memory Address: 123456789)
Height: 1.75 (Type: <class 'str'>, Memory Address: 123456789)
Favourite Number: 7 (Type: <class 'str'>, Memory Address: 123456789)

Your birth year is approximately: 2008 (based on your age of 18)

Thank you for using the Personal Data Collector. Goodbye!
