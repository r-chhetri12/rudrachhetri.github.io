<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Rudra Chhetri - Data Analyst Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f5f5f5;
      color: #222;
    }
    header {
      background: #111827;
      color: #f9fafb;
      padding: 30px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 28px;
    }
    header p {
      margin: 8px 0 0;
      font-size: 14px;
      opacity: 0.9;
    }
    .container {
      max-width: 900px;
      margin: 20px auto;
      background: #ffffff;
      padding: 20px 25px 30px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      border-radius: 10px;
    }
    h2 {
      border-bottom: 2px solid #e5e7eb;
      padding-bottom: 6px;
      margin-top: 25px;
      font-size: 20px;
    }
    .project {
      margin-top: 18px;
      padding: 15px;
      border-radius: 8px;
      background: #f9fafb;
      border: 1px solid #e5e7eb;
    }
    .project h3 {
      margin: 0 0 5px;
      font-size: 18px;
    }
    .tagline {
      font-size: 14px;
      color: #4b5563;
      margin-top: 5px;
    }
    .pill {
      display: inline-block;
      margin: 3px 4px 0 0;
      padding: 3px 8px;
      font-size: 11px;
      border-radius: 999px;
      background: #e5e7eb;
      color: #374151;
    }
    ul {
      padding-left: 18px;
      margin-top: 6px;
    }
    .links a {
      display: inline-block;
      margin-right: 10px;
      margin-top: 8px;
      font-size: 12px;
      text-decoration: none;
      color: #2563eb;
    }
    .skills-list span {
      display: inline-block;
      margin: 4px 6px 0 0;
      padding: 4px 10px;
      font-size: 12px;
      border-radius: 999px;
      background: #eef2ff;
      color: #1f2937;
    }
    footer {
      text-align: center;
      font-size: 12px;
      color: #6b7280;
      margin: 20px 0 30px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Rudra Chhetri</h1>
    <p>Data Analyst • SQL | Python | Power BI | DAX | Excel</p>
  </header>

  <div class="container">
    <h2>About Me</h2>
    <p class="tagline">
      I’m an aspiring data analyst with hands-on projects in churn analysis, sales analytics,
      and business dashboards. I work with SQL, Python, Power BI, DAX, and Excel to turn raw data
      into clear insights for decision-making.
    </p>

    <h2>Projects</h2>

    <div class="project">
      <h3>Telecom Customer Churn Analysis</h3>
      <div>
        <span class="pill">SQL</span>
        <span class="pill">Python</span>
        <span class="pill">Chi-square</span>
        <span class="pill">Power BI</span>
      </div>
      <p class="tagline">Analyzed 7K+ telecom customers to understand drivers of churn and revenue loss.</p>
      <ul>
        <li>Overall churn rate: 27%, with highest churn (62%) in 0–1 month tenure segment.</li>
        <li>Senior citizens (60+) churn rate: 35% vs 22% for under-30 segment.</li>
        <li>Lost revenue from churned customers: $8M (26% of total $31M revenue).</li>
        <li>Fiber Optic and month-to-month contracts are the riskiest segments.</li>
      </ul>
      <div class="links">
        <a href="YOUR_TELECOM_GITHUB_LINK" target="_blank">View on GitHub</a>
        <a href="YOUR_TELECOM_DASHBOARD_IMAGE_OR_PBIX_LINK" target="_blank">View Dashboard</a>
      </div>
    </div>

    <div class="project">
      <h3>HR / Employee Attrition Analysis</h3>
      <div>
        <span class="pill">SQL</span>
        <span class="pill">Python</span>
        <span class="pill">Power BI</span>
      </div>
      <p class="tagline">Explored employee attrition patterns to identify high-risk groups and root causes.</p>
      <ul>
        <li>51% overall attrition, with very high exits in the first year of employment.</li>
        <li>Higher churn among older employees (46+) and even among high performers.</li>
        <li>Production department and frontline roles like Laborer/Technician show the most exits.</li>
      </ul>
      <div class="links">
        <a href="YOUR_HR_GITHUB_LINK" target="_blank">View on GitHub</a>
        <a href="YOUR_HR_DASHBOARD_IMAGE_OR_PBIX_LINK" target="_blank">View Dashboard</a>
      </div>
    </div>

    <div class="project">
      <h3>Sales Performance Dashboard</h3>
      <div>
        <span class="pill">Power Query</span>
        <span class="pill">SQL</span>
        <span class="pill">DAX</span>
        <span class="pill">Power BI</span>
      </div>
      <p class="tagline">Built an end-to-end sales performance dashboard with dynamic measures and trends.</p>
      <ul>
        <li>Total sales: $34M, total profit: $21M (60.29% margin), total cost: $14M.</li>
        <li>New Zealand and Bars category are top drivers of sales and profit.</li>
        <li>Peanut Butter Cubes product has a 66.71% profit margin.</li>
        <li>Used a DAX-based measure selector to switch between monthly Sales, Boxes, Shipments, Profit, and Cost.</li>
      </ul>
      <div class="links">
        <a href="YOUR_SALES_GITHUB_LINK" target="_blank">View on GitHub</a>
        <a href="YOUR_SALES_DASHBOARD_IMAGE_OR_PBIX_LINK" target="_blank">View Dashboard</a>
      </div>
    </div>

    <h2>Skills</h2>
    <div class="skills-list">
      <span>SQL (joins, aggregates, window functions)</span>
      <span>Python (Pandas, analysis, chi-square)</span>
      <span>Power BI (DAX, Power Query, dashboards)</span>
      <span>Excel (pivot tables, formulas)</span>
      <span>Data Cleaning & EDA</span>
      <span>Business Reporting</span>
    </div>

    <h2>Contact</h2>
    <p>
      Email: <b>YOUR_EMAIL_HERE</b><br />
      LinkedIn: <a href="YOUR_LINKEDIN_LINK" target="_blank">View Profile</a><br />
      GitHub: <a href="YOUR_GITHUB_PROFILE_LINK" target="_blank">View Repositories</a>
    </p>
  </div>

  <footer>
    © 2025 · Portfolio of Rudra Chhetri
  </footer>
</body>
</html>
