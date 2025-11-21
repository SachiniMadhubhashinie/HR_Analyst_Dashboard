# HR_Analyst_Dashboard
This HR Analytics Dashboard provides a clear overview of employee distribution, attrition, and job satisfaction trends. It visualizes key metrics such as department-wise attrition, age groups, education fields, and gender-based insights. The dark purple and maroon theme enhances readability while presenting workforce patterns at a glance.

<h2>Project Overview</h2>
<p>This project utilizes organizational HR data to conduct a deep analysis of employee behavior, satisfaction, and performance metrics. The primary objective is to identify factors contributing to Attrition, understand the relationship between job satisfaction and employee roles, and provide data-driven recommendations to improve retention and overall workforce performance.</p>


<h2>Problem Statement</h2>
<ul>
  <li>What are the primary demographic, job-related, and satisfaction factors that correlate most strongly with Attrition (Yes/No)?</li>
  <li>How do key metrics like Monthly Income, Total Working Years, and Years At Company differ between employees who stay and those who leave?</li>
  <li>Which departments and job roles show the highest risk of attrition, especially when combined with factors like Over Time?</li>
  <li>How does the Performance Rating relate to Percent Salary Hike and job satisfaction metrics?</li>
</ul>

<h2>Technology Stack</h2>
Data Storage : CSV File<br>
Visualization	: Power BI

<h2>Key Performance Indicators (KPIs)</h2>

<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th>KPI</th>
      <th>Business Significance</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Attrition Rate</td>
      <td>The most critical measure of workforce stability.</td>
    </tr>
    <tr>
      <td>Average Tenure</td>
      <td>Indicates long-term employee engagement and retention success.</td>
    </tr>
    <tr>
      <td>Engagement Score</td>
      <td>Measures how connected and happy employees are.</td>
    </tr>
    <tr>
      <td>Performance Gap</td>
      <td>Identifies high and low-performing organizational units.</td>
    </tr>
    <tr>
      <td>Salary Hike Effectiveness</td>
      <td>Tests if compensation increases are adequately motivating employees to stay.</td>
    </tr>
  </tbody>
</table>

<h2>Chart Requirements and Analysis</h2>

<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th>Chart Type</th>
      <th>Analysis Goal</th>
      <th>Data Columns Required</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Density/Box Plots</td>
      <td>Distribution of Monthly Income and Total Working Years segmented by Attrition</td>
      <td>Monthly Income, Total Working Years, Attrition</td>
    </tr>
    <tr>
      <td>Bar Chart</td>
      <td>Attrition Rate by Categorical Features: Job Role, Department, Marital Status, and Over Time</td>
      <td>Attrition, Categorical Features</td>
    </tr>
    <tr>
      <td>Scatter Plot</td>
      <td>Relationship between Distance From Home and Attrition</td>
      <td>Distance From Home, Attrition</td>
    </tr>
    <tr>
      <td>Heatmap/Correlation Matrix</td>
      <td>Correlation between all numerical satisfaction metrics (Environment Satisfaction, Job Satisfaction, etc.)</td>
      <td>Numerical Satisfaction Columns</td>
    </tr>
    <tr>
      <td>Pie/Donut Chart</td>
      <td>Breakdown of Attrition by CF_age band (Age Group)</td>
      <td>Attrition, CF_age band</td>
    </tr>
  </tbody>
</table>

<h2>Key Insights & Recommendations</h2>
<p>Based on HR attrition data, here are key findings and recommendations:</p>

<h3>Key Insights</h3>
<ul>
  <li><strong>Overtime Crisis:</strong> Employees reporting Over Time (Yes) have 3X higher attrition, indicating burnout risk.</li>
  <li><strong>Compensation Sensitivity:</strong> Attrition is higher among employees earning below $5,000/month or receiving low salary hikes (11-13%).</li>
  <li><strong>High-Risk Roles:</strong> Laboratory Technicians and Sales Representatives show high turnover and low Job Satisfaction (&lt;2.5).</li>
  <li><strong>Tenure Risk:</strong> Employees with 3-5 years at the company have the highest attrition, highlighting mid-career retention challenges.</li>
</ul>

<h3>Recommendations</h3>
<ul>
  <li><strong>Mandatory Overtime Audit:</strong> Cap overtime and introduce flex-time or compensatory time-off for high-burnout departments.</li>
  <li><strong>Targeted Compensation Review:</strong> Adjust salaries for employees earning below $5,000/month and improve low-end salary hikes to boost retention.</li>
  <li><strong>Role-Specific Engagement:</strong> Offer professional development and mentorship for high-risk roles to increase Job Satisfaction.</li>
  <li><strong>Mid-Tenure Retention Program:</strong> Launch a 'Three-Year Milestone' program with benefits, stock options, or promotion opportunities for 3-5 year tenure employees.</li>
</ul>





