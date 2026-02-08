Project Overview
This project is an internal business tool developed to help Customer Success Managers (CSMs) identify high-risk properties within their portfolio. By automating the analysis of user adoption and conversion metrics, the tool reduces manual audit time and allows for proactive client intervention.

The Problem
CSMs often manage hundreds of accounts via static spreadsheets. Manually identifying which properties fall below health thresholds is time-consuming and prone to human error, leading to delayed responses to potential churn.

The Solution
A dynamic web application built in Retool that allows users to:
- Upload property data in both .csv and .xlsx (Excel) formats.
- Automatically Flag properties as "High Risk" based on custom thresholds:
-- User Adoption: < 30%
-- Conversion Rate: < 20%
- Visualize KPIs including Total Property Count, At-Risk Property Count, and Portfolio Risk Percentage.

Technical Highlights
- Dynamic File Parsing: Implemented JavaScript logic to handle multi-sheet Excel workbooks and flat CSV files interchangeably.
- Custom Transformers: Developed JavaScript-based transformers to process raw data and inject calculated "Risk Status" fields into the UI layer.
- Interactive UI: Leveraged Retool’s component library to create a responsive dashboard with conditional formatting for immediate visual insight.

Repository Contents
- Property_Risk_Filter.json: The Retool application export file.
- Sample_Data.xlsx: A test file to demonstrate the tool's functionality.

How to Use
- Import the .json file into your Retool environment.
- Upload the provided Sample_Data.xlsx.
