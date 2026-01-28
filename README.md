🧹 Customer & Product Text Analysis for Marketing Insights

📌 Project Overview

This project focuses on cleaning and validating customer and product text data using Python. The goal was to improve data quality for a simulated marketing and operations use case where accurate store information is 
critical for reporting, analysis, and customer engagement.

Poor data quality can lead to misleading insights, broken systems, and lost trust. This project demonstrates how analysts can prevent those issues using simple but powerful automation techniques.

🧠 Business Problems Addressed

The project answers the following questions:

How can we correct ZIP Codes when leading zeros are missing?

How can we identify invalid ZIP Codes that do not follow U.S. standards?

How can we validate store URLs to ensure correct protocols and ID formats?

How can we automate these checks to avoid manual data cleaning?

🔧 Tools & Technologies

Python

String manipulation

Conditional logic (if / else)

Custom functions

Data validation rules

🔍 Analysis & Development Process

1️⃣ ZIP Code Validation Function

A custom function was created to:

Check ZIP Code length

Add missing leading zeros when appropriate

Flag invalid ZIP Codes that do not meet formatting rules

Why this step was done:

ZIP Codes are often imported as numbers, which removes leading zeros and creates inaccurate location data.

2️⃣ ZIP Code Testing

Multiple test cases were used to confirm:

Valid ZIP Codes are preserved

Fixable ZIP Codes are corrected

Invalid ZIP Codes are flagged

Why this step was done:

Testing ensures the logic works before applying it to real datasets.

3️⃣ Store URL Validation Function

A second function checks:

Whether the URL uses the correct https: protocol

Whether the store ID is exactly seven characters long

Why this step was done:

Invalid URLs and IDs can cause broken links, failed tracking, and inaccurate reporting.

4️⃣ URL Testing & Error Messaging

The function clearly identifies:

Invalid protocols

Invalid store IDs

Valid URLs that pass all checks

Why this step was done:

Clear error messages make it easier for teams to fix issues quickly.

📊 Key Insights

Data errors often come from formatting issues, not missing data

Automating validation saves time and prevents repeated mistakes

Clean text data improves downstream analysis and reporting accuracy

🎯 Business Impact

This approach helps organizations:

Improve reporting accuracy

Reduce manual data cleaning

Increase trust in dashboards and insights

Catch errors early in the data pipeline

🚀 Next Steps

Apply functions to larger datasets

Log validation errors for reporting

Extend validation rules to emails, phone numbers, or product SKUs






