JMeter Easy Calculation Assignment

Author Details

- Name: Keshav Agarwal
- Employee ID: 85009852

Project Description

This project demonstrates performance testing of the Easy Calculation website using Apache JMeter. The test plan was designed to simulate multiple users accessing different modules of the application and to analyze response times and performance metrics.

Tools Used

- Apache JMeter 5.6.3
- Java
- Git & GitHub

Test Configuration

Thread Group

- Number of Users (Threads): 10
- Ramp-Up Period: 5 Seconds
- Loop Count: 2

Requests Executed

The following application modules were tested:

1. Converter
2. Formulas
3. Currencies
4. Charts
5. Examples
6. Tutorials
7. Answers
8. Dictionary
9. Download
10. Calculators

Controllers Used

- Loop Controller
- Random Controller

Timer Used

- Constant Timer (5 Seconds)

Listeners Used

- View Results Tree
- View Results in Table
- Aggregate Graph

Test Execution Summary

- Total Samples Executed: 200
- Successful Requests: 100%
- Errors: 0
- Performance metrics captured using Aggregate Graph and View Results in Table.

Project Structure

EasyCalculation_TG/
│
├── Easy Calculation.jmx
├── statistics.csv
├── README.md
├── Aggregate Graph.png
├── View Results Table.png
└── HTML_Report/

Key Observations

- All requests executed successfully.
- No failed requests were observed during execution.
- Response times remained within acceptable limits.
- Aggregate Graph was generated to visualize performance statistics.

How to Run

1. Open Apache JMeter.
2. Open "Easy Calculation.jmx".
3. Click the Start button to execute the test.
4. View results in:
   - View Results Tree
   - View Results in Table
   - Aggregate Graph
5. Generate the HTML Report using:

jmeter -n -t "Easy Calculation.jmx" -l results.jtl -e -o HTML_Report

Conclusion

The Easy Calculation application was successfully tested using Apache JMeter. All configured requests executed without errors, and the performance metrics were collected and analyzed using JMeter listeners and reports.
