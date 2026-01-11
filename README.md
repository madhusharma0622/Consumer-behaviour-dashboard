<h1>📊 Customer Behavior Dashboard – Power BI Portfolio Project</h1>

<h2>📌 Project Overview</h2>
<p>
This project showcases an end-to-end Power BI dashboard designed to analyze customer purchasing behavior across demographics, subscription status, product categories, and age groups. The dashboard enables business stakeholders to quickly identify revenue drivers, customer segments, and sales patterns for data-driven decision-making.
</p>
<ul>
  <li>🔹 <strong>Objective:</strong> Transform raw customer data into actionable insights using Power BI</li>
  <li>🔹 <strong>Target Audience:</strong> Business leaders, marketing teams, and recruiters evaluating analytics skills</li>
</ul>

<h2>🛠 Tools & Technologies</h2>
<ul>
  <li>Power BI Desktop</li>
  <li>Power Query (ETL)</li>
  <li>DAX (Measures & KPIs)</li>
  <li>Data Modeling</li>
  <li>Data Visualization Best Practices</li>
</ul>

<h2>📂 Dataset Description</h2>
<p>The dataset contains customer-level transactional and demographic data with the following key attributes:</p>
<ul>
  <li>Customer ID</li>
  <li>Gender</li>
  <li>Age Group</li>
  <li>Subscription Status (Yes / No)</li>
  <li>Product Category (Clothing, Accessories, Footwear, Outerwear)</li>
  <li>Purchase Amount</li>
  <li>Sales Quantity</li>
  <li>Shipping Type</li>
  <li>Customer Review Rating</li>
</ul>
<p><em>(Dataset is simulated for portfolio purposes)</em></p>

<h2>🔄 Step-by-Step Project Workflow </h2>

<h3>1️⃣ Data Import</h3>
<ul>
  <li>Imported raw data into Power BI Desktop</li>
  <li>Verified data types and column consistency</li>
</ul>

<h3>2️⃣ Data Cleaning & Transformation (Power Query)</h3>
<ul>
  <li>Removed duplicates and null values</li>
  <li>Standardized category names and age groups</li>
  <li>Created derived columns:
    <ul>
      <li>Age Group Buckets</li>
      <li>Subscription Flags</li>
    </ul>
  </li>
  <li>Ensured numerical columns were optimized for aggregation</li>
</ul>

<h3>3️⃣ Data Modeling</h3>
<ul>
  <li>Established relationships between customer and transaction fields</li>
  <li>Optimized model for performance</li>
  <li>Ensured star-schema–like structure where applicable</li>
</ul>

<h3>4️⃣ DAX Measures Created</h3>
<p>Key KPIs built using DAX:</p>
<ul>
  <li>Total Customers = DISTINCTCOUNT(Customer[Customer ID])</li>
  <li>Average Purchase Amount = AVERAGE(Sales[Purchase Amount])</li>
  <li>Average Rating = AVERAGE(Customer[Review Rating])</li>
  <li>Total Revenue = SUM(Sales[Purchase Amount])</li>
  <li>Total Sales Quantity = SUM(Sales[Quantity])</li>
</ul>

<h3>5️⃣ Dashboard Design & Visuals</h3>
<p>The dashboard was designed with business clarity and storytelling in mind.</p>
<ul>
  <li>🔹 <strong>KPI Cards</strong>
    <ul>
      <li>Total Customers: 3.9K</li>
      <li>Average Purchase Amount: $59.76</li>
      <li>Average Review Rating: 3.75</li>
    </ul>
  </li>
  <li>🔹 <strong>Visual Insights</strong>
    <ul>
      <li>Subscription Status Distribution (Donut Chart)</li>
      <li>Revenue by Product Category (Bar Chart)</li>
      <li>Sales by Product Category (Bar Chart)</li>
      <li>Purchases by Age Group (Horizontal Bar)</li>
      <li>Sales by Age Group (Horizontal Bar)</li>
    </ul>
  </li>
</ul>

<h3>6️⃣ Interactive Filters (Slicers)</h3>
<p>Implemented slicers to allow dynamic analysis:</p>
<ul>
  <li>Subscription Status</li>
  <li>Gender</li>
  <li>Product Category</li>
  <li>Shipping Type</li>
</ul>
<p>These filters update all visuals simultaneously, enabling quick exploratory analysis.</p>

<h2>📈 Key Business Insights</h2>
<ul>
  <li>73% of customers are non-subscribers, highlighting subscription growth opportunities</li>
  <li>Clothing is the top-performing category in both revenue and sales</li>
  <li>Young Adults contribute the highest purchase volume</li>
  <li>Subscription customers show higher engagement and consistency</li>
</ul>

<h2>🎨 Dashboard Preview</h2>

<h2>🚀 What This Project Demonstrates</h2>
<ul>
  <li>✔ Strong understanding of Power BI end-to-end workflow</li>
  <li>✔ Hands-on experience with DAX & Power Query</li>
  <li>✔ Ability to convert raw data into executive-ready dashboards</li>
  <li>✔ Focus on business insights, not just visuals</li>
</ul>
