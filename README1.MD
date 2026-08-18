# Simple Interest Calculator

A lightweight, console-based Java application designed to calculate simple interest based on user inputs for principal amount, annual interest rate, and time period in years.

## Table of Contents
- [Features](#features)
- [Formula Used](#formula-used)
- [Prerequisites](#prerequisites)
- [How to Run](#how-to-run)
- [Example Usage](#example-usage)

## Features
- **User-Friendly Interface:** Prompts users clearly for financial inputs.
- **Accurate Floating-Point Math:** Handles decimal values for precise financial calculations.
- **Instant Results:** Displays the calculated simple interest and final total amount immediately.

## Formula Used
The application calculates simple interest using the standard financial formula:

\[\text{Simple Interest} = \frac{P \times R \times T}{100}\]

Where:
- \(P\) = Principal amount (the initial sum of money)
- \(R\) = Annual interest rate (in percentage)
- \(T\) = Time period (in years)

The total accumulated value is calculated as:
\[\text{Total Amount} = P + \text{Simple Interest}\]

## Prerequisites
To run this application locally, you need to have the following installed:
- **Java Development Kit (JDK):** Version 8 or higher.
- A terminal, command prompt, or an Integrated Development Environment (IDE) like IntelliJ IDEA, Eclipse, or VS Code.

## How to Run
Follow these steps to clone and run the application locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   ```
2. **Navigate into the project directory:**
   ```bash
   cd YOUR_REPOSITORY_NAME
   ```
3. **Compile the Java file:**
   ```bash
   javac SimpleInterestCalculator.java
   ```
4. **Run the compiled program:**
   ```bash
   java SimpleInterestCalculator
   ```

## Example Usage
When you execute the program, the interaction looks like this:

```text
--- Simple Interest Calculator ---
Enter the Principal amount (\$): 10000
Enter the Annual Interest Rate (%): 5.5
Enter the Time period (in years): 3

--- Results ---
Calculated Simple Interest: \$1650.00
Total Value after 3 years: \$11650.00
```
