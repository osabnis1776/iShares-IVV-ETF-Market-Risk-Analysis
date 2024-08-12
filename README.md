Market Risk Analysis for S&P 500 Index IVV ETF (Alteryx Designer, Python)

Overview

This project conducts a market risk analysis of the S&P 500 Index IVV ETF using Alteryx and Python. The analysis focuses on key market risk indicators such as Value at Risk (VaR), Expected Shortfall (ES), Sharpe Ratio, and Max Drawdown. 

License

BSD 2-Clause License

Copyright (c) 2024, Omkar Sabnis

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution. THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


Project Objectives

Import and Preprocess Data: Fetch historical data for the S&P 500 Index IVV ETF from the internet for the last 5 years.
Calculate Key Risk Metrics:
Value at Risk (VaR): Measure the maximum expected loss at a specific confidence level.
Expected Shortfall (ES): Estimate the average loss beyond the VaR.
Sharpe Ratio: Assess risk-adjusted returns.
Max Drawdown: Identify the largest peak-to-trough decline.
Visualize Results: Create visual representations of the calculated metrics using Alteryx.

Project Structure

/data: Folder for raw and processed datasets.
/workflows: Contains the Alteryx workflow files.
/visualizations: Output graphs and visualizations created during the project.
README.md: Project documentation (this file).

Prerequisites

Alteryx Designer
Alteryx license required for running workflows.

Installation and Setup

Clone the Repository:
bash
Copy code
git clone https://github.com/username/market-risk-analysis-ivv-etf.git
cd market-risk-analysis-ivv-etf
Open and Run Alteryx Workflow:
Open the Alteryx workflow file in Alteryx Designer.
Run the workflow to perform the risk analysis and generate visualizations.

Results

The results, including VaR, ES, Sharpe Ratio, and Max Drawdown, are dynamically calculated each time the program is executed. These metrics provide insights into the risk exposure of the S&P 500 Index IVV ETF over the analyzed period.


Acknowledgments

Created by: Omkar Sabnis
Tools Used: Alteryx Designer, Python.



Alteryx Canvas
<img width="770" alt="Screenshot 2024-08-12 at 5 02 25 PM" src="https://github.com/user-attachments/assets/baf1e99f-b428-4b81-a523-850436f8ef11">

Histogram representing Moving Average Return
<img width="688" alt="Screenshot 2024-08-12 at 5 01 42 PM" src="https://github.com/user-attachments/assets/5f1dd9e1-9fbb-43b4-9832-a9a72458f7a2">

Bar Chart Displaying Max Drawdown and Moving Average Return
<img width="1130" alt="Screenshot 2024-08-12 at 4 59 20 PM" src="https://github.com/user-attachments/assets/93302805-3050-4da6-8f5c-9fb0cb8712ff">

Risk Metrics
<img width="359" alt="Screenshot 2024-08-12 at 5 46 48 PM" src="https://github.com/user-attachments/assets/3a121734-752f-4e55-ba64-be9d6d709a65">
