Hi, I'm Davron 👋
Python & Data Analytics | Fintech & Compliance

I'm a fintech and banking professional with 6 years of experience in compliance and financial services.

I'm currently expanding my technical skills in Python, SQL, and data analysis, with a focus on using technology and data to solve practical problems in financial services.

🛠️ Technical Skills
Data Analysis & Excel — professional experience analyzing data, identifying issues, and supporting problem-solving in fintech
Power BI — data visualization, reporting, and dashboard creation
Python — currently learning, with a focus on data analysis and automation
SQL — developing knowledge of querying and working with structured data
Git & GitHub — version control and project documentation. 

💼 Domain Experience

With 6 years of experience in fintech and banking, my professional background includes:

Compliance and regulatory processes
Financial data analysis and reporting
Identifying issues and discrepancies in data
Risk and controls
Process analysis and improvement
Supporting teams through data-driven problem-solving

I'm particularly interested in combining this domain knowledge with Python, SQL, and data analysis to build practical solutions for financial and compliance-related problems.

📊 What I'm Working On
I'm using GitHub to document my transition into Python and data-focused work through practical projects.

I'm currently focusing on:

Building practical projects with Python
Analyzing and visualizing data
Learning SQL for data querying and analysis
Exploring automation and how it can improve repetitive processes
Applying my fintech and compliance background to data-focused projects

🎯 Career Direction

My goal is to combine my experience in fintech, banking, and compliance with technical skills in Python, SQL, and data analysis.

I'm particularly interested in data-focused and technology-driven roles within financial services, where I can use both my domain knowledge and technical skills to solve practical problems.


VS Code
 └── Jupyter Notebook (.ipynb)
      └── Python 3.11
           └── Pandas
                └── NYC Taxi Dataset

                "I used Python and Pandas for analysis, working in Jupyter Notebooks within VS Code.


 Revenue Analysis Findings
Revenue peaks during evening rush hours (3 PM-7 PM).
The highest revenue-generating hour is 6 PM, producing approximately 7.79 million in total trip revenue.
The same period also records the highest trip volume, indicating strong demand-driven revenue growth.
Taxi operators may benefit from increasing driver availability during peak evening periods to maximize revenue capture.

Most revenue comes in during the evening rush hour (4 PM–7 PM), while the highest average revenue per trip is seen between 4 AM and 6 AM. This suggests that early-morning trips are less frequent but tend to bring in more revenue per ride.

Premium Long-Haul: $90.44
Long Distance:     $48.42
Urban Traveler:    $29.26
Short Distance:    $19.55

Short Distance      $39.59M
Urban Traveler      $29.46M
Long Distance       $26.55M
Premium Long-Haul   $13.08M

Customer segmentation analysis identified four traveler groups based on trip distance. Short-distance travelers represented the largest segment with over 2 million trips and generated the highest total revenue ($39.6M). However, Premium Long-Haul travelers generated the highest average revenue per trip ($90.44), indicating a distinct high-value customer segment.


Finding

Short-distance travelers represent the largest customer segment, accounting for more than 2 million trips.

This suggests NYC taxis are primarily used for relatively short urban journeys.

Revenue by Traveler Segment

Short Distance: 36.4% of total revenue (largest contributor)
Urban Traveler: 27.1% of total revenue
Long Distance: 24.4% of total revenue
Premium Long-Haul: 12.0% of total revenue

Key Insight: Short-distance trips drive revenue through high volume, while Premium Long-Haul trips generate the highest value per ride.

Payment Type       Trips       Avg Revenue    Total Revenue
----------------------------------------------------------
Credit Card      2,249,747        29.61          66.6M
Cash               314,043        23.41           7.4M
No Charge           16,641         8.93           0.1M
Dispute             56,400         1.70           0.1M
Flex Fare        1,088,058        31.68          34.5M

Credit card payments dominate the business, generating 66.6M in revenue with a higher average trip value (29.61) than cash payments (23.41). Flex Fare trips also represent a significant revenue source, contributing 34.5M across 1.09 million trips. Payment exceptions such as No Charge and Dispute transactions contribute only a small fraction of total revenue, indicating that the vast majority of business activity comes from standard customer-paid trips. Payment type codes are defined by the Yellow Taxi Trip Records data dictionary as: 0 = Flex Fare, 1 = Credit Card, 2 = Cash, 3 = No Charge, 4 = Dispute.


Revenue efficiency analysis revealed that Short Distance travelers are the most profitable segment on a per-mile basis, generating 18.52 revenue per mile. In contrast, Premium Long-Haul travelers generate the highest revenue per trip ($90.44) but the lowest revenue efficiency (0.92 per mile). Overall, revenue efficiency decreases as trip distance increases, indicating that shorter trips deliver greater value relative to distance traveled.

Analysis identified 125,738 trips with a recorded distance of zero miles. Despite reporting no travel distance, these trips generated an average fare of $27.97 and an average total charge of $34.30. The dataset also contains extreme values, including fares ranging from -$990 to $2,500 and tips ranging from -$20 to $489.99. These observations suggest that many zero-distance trips are not simple cancellations and may represent billing adjustments, special fare cases, system-recording issues, or other operational anomalies requiring further investigation.

125,738 zero-distance trips
Average total charge = $34.30
Maximum charge = $2,500
Minimum total amount = -$991

Distance outlier analysis identified multiple trips with recorded distances exceeding 180,000 miles, including a maximum value of 269,097 miles. Despite these extreme distances, the associated fares ranged between $16 and $82, which is inconsistent with normal taxi pricing behavior. These records are likely data-quality anomalies caused by measurement, reporting, or system-recording errors.
