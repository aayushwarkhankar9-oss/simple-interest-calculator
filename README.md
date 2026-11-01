# Simple Interest Calculator

## Introduction
This project is a simple interest calculator developed using Python. It calculates simple interest based on the principal amount, rate of interest, and time period.

## Formula
Simple Interest = (Principal × Rate × Time) / 100

## Python Code

```python
principal = float(input("Enter principal amount: "))
rate = float(input("Enter rate of interest: "))
time = float(input("Enter time in years: "))

simple_interest = (principal * rate * time) / 100

print("Simple Interest:", simple_interest)
