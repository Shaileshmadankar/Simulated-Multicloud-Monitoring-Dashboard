
1. Project Title : Simulated Multi-cloud Monitoring Dashboard

2. Description :

The Simulated Multicloud Analytics Dashboard is a visually engaging and analytical Power BI report designed to show cloud service usage  and compare between three major cloud provider (AWS, GCP and AZURE) across some continents. The dashboard focuses on highlighting major Cloud services most frequently used by cloud users like Virtual machine, Cpu utilization, Memory, Ram , price per unit, utilization with cost.  This tool is intended for use by  analysts for the cloud user and data-driven strategists who seek to understand usage and characteristics of cloud by the usage.

3. Tech Stack

• 📊 Power BI Desktop – Main data visualization platform used for report creation.
• 📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.
• 🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.
• 📝 Data Modeling – Relationships established among tables (resorts, snow, and data_dictionary) to enable cross-filtering and aggregation.
• 📁 File Format – .pbix for development and .png for dashboard previews.


4. Data Source

Source: kaggle Cloud Dataset.

Data collected from Kaggle’s public cloud usage dataset, containing metrics such as CPU, RAM, cost, and latency, including details of service which are used like Vcpu, CPU usage, Memory usage, Ram utilization ,prices per unit , cost as well as a complementary table with the cloud provider give the overall cloud service usage.


5. Features / Highlights
• Business problem 
The reason to design these simulated dashboard is to calculate which services are most frequently used and carry the highest load which are primary service in it and has large no load on service like vm_cpu, virtual memory to run and perform the task for developer or user. 


• Goal of the dashboard 
The main goal of this dashboard is to monitor and analyze the performance, cost, and utilization of multiple cloud providers (AWS, Azure, and Google Cloud) in a single view.

Track and compare CPU, memory, and network utilization across providers.
Evaluate the cost efficiency of different virtual machines and regions.
Identify patterns in latency and throughput that affect overall cloud performance.
Present insights that can help businesses choose the most efficient and cost-effective cloud service.

• Walk through of key visuals :

KPI Cards:
Display the average CPU utilization, average memory usage, and total cloud cost to provide a quick overview of overall performance.

Bar Chart (Latency per Region):
Compares the average latency across different regions to highlight which areas deliver faster response times.

Pie Chart (Cloud Provider by Price per Hour):
Shows the cost distribution among AWS, Azure, and Google Cloud, helping visualize which provider is more cost-intensive.

Scatter Chart (Utilization vs Cost):
Display the relationship between cloud provider over the latency ms through the througput making it easier to identify the most provider.


Slicers / Filters:
Allow users to select a specific cloud provider or region so that all visuals update dynamically to reflect the chosen data.

Dashboard Layout:
Organized into multiple pages for better readability — Page 1 covers utilization and cost insights latency of provider , while Page 2 throughput, and utilization efficiency .

• Business impact & Insights

The simulated dashboard helps businesses monitor and compare multi-cloud performance in one unified view, which can support data-driven decision-making.

By identifying which provider delivers higher utilization at lower cost, companies can optimize their cloud spending and improve efficiency.

Insights from latency and throughput visuals highlight regions or VM types that may need performance tuning.

The project demonstrates how Power BI can simplify complex cloud data into clear visuals that support strategic planning and cost optimization.

Overall, this analysis can help organizations reduce unnecessary costs, enhance performance, and achieve better resource allocation across cloud platforms.



• Goal of the Dashboard To deliver an interactive visual tool that: 

Monitors and compares the performance, cost, and utilization of multiple cloud providers (AWS, Azure, and Google Cloud).
Identifies trends in CPU, memory, and network usage for better operational decisions.
Highlights cost inefficiencies and performance gaps across regions or VM types.
Provides actionable insights to help organizations choose the most efficient and cost-effective cloud services.
Demonstrates my skills in building a professional Power BI dashboard with real-world analytical use cases.

• Walkthrough of Key Visuals


KPI Cards:
Show Average CPU Utilization, Average Memory Usage, and Total Cloud Cost, providing a quick snapshot of overall system performance.

Bar Chart (Latency per Region):
Displays latency variations across regions to help identify which regions offer better network performance.

Pie Chart (Cloud Provider by Price per Hour):
Illustrates the share of cost among AWS, Azure, and Google Cloud, helping visualize cost distribution by provider.

Scatter Chart (Utilization vs Cost):
Reveals the relationship between utilization efficiency and total cost, indicating which provider offers the best performance for the price.

Slicers / Filters:
Allow users to filter visuals by Cloud Provider or Region, making the dashboard dynamic and interactive.

Dashboard Pages:

Page 1: Focuses on overall utilization and cost efficiency and latency.

Page 2: Highlights network performance metrics  and throughput.


6. Screenshots / Demos
Show what the dashboard looks like.
![Dashboard Screenshot](https://github.com/Shaileshmadankar/Simulated-Multicloud-Monitoring-Dashboard/blob/main/MultiCloud%20Dashboard%20Screenshot%201.png)

