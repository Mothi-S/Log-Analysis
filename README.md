# Log Analysis Project

## Overview
This project analyzes log files to detect suspicious activity, such as multiple failed login attempts, and provides insights into the most accessed endpoints. The analysis is done using Python and pandas, with the results saved to CSV files for further review.

## Features
- **Failed login attempt detection**: Identifies IP addresses with multiple failed login attempts, helping to detect potential brute-force attacks or unauthorized access attempts.
- **Most accessed endpoints**: Analyzes the log files to identify the most frequently accessed endpoints.
- **Suspicious activity**: Flags IP addresses with an unusually high number of failed login attempts (threshold set to 10).

## Installation

### Requirements
- Python 3.x
- Pandas library

You can install the required Python libraries using the following command:
```bash
pip install pandas
