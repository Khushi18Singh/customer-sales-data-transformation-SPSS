# customer-sales-data-transformation-SPSS
Data cleaning, transformation, and preparation of Superstore sales data using IBM SPSS Modeler
customer-sales-data-transformation-SPSS
Data cleaning, transformation, and preparation of Superstore sales data using IBM SPSS Modeler

📊 Customer Sales Data Transformation & Predictive Analysis (IBM SPSS Modeler Case Study) 📌 Project Overview

This project focuses on data cleaning, transformation, enrichment, and preparation of customer sales data using IBM SPSS Modeler. The objective is to convert raw sales data into a clean, structured, and analysis-ready dataset that can be used for predictive analytics, visualization, and business decision-making.

The project is based on the Sample – Superstore Sales Dataset and demonstrates practical usage of key SPSS Modeler nodes used in real-world data analytics workflows.

🎯 Objectives

Define one record per customer by removing duplicate entries Clean and standardize raw sales data Create meaningful derived and categorical fields Prepare data for predictive modeling and visualization Generate a final integrated dataset suitable for Power BI / Excel / Reporting

🛠 Tools & Technologies Used

IBM SPSS Modeler – Data preprocessing & transformation Excel Dataset – Sample Superstore Sales Data

SPSS Modeler Nodes Used:

Type Node Distinct Node Aggregate Node SetToFlag Node Derive Node Reclassify Node Binning Node Transform Node Merge Node

📂 Dataset Name: Sample – Superstore Sales Type: Customer sales transaction data Contains: Sales, Profit, Product Category, Region, Order Priority, Discount, etc.

🔄 Project Workflow (Step-by-Step)

Step 1: Import Dataset

Imported Excel dataset using Excel Source Node Previewed records to understand data structure

Step 2: Assign Field Roles & Measurement Levels

Used Type Node Defined:

Numeric fields Categorical fields Input / Target / None roles Ensured accurate processing for further transformations

Step 3: Remove Duplicate Records

Applied Distinct Node Used Row ID as the key field Ensured unique records per customer

Step 4: Aggregate Data

Used Aggregate Node Calculated: Total Sales (Sum) Record Count per Row ID Created summarized metrics for analysis

Step 5: Create Category Flags

Used SetToFlag Node Converted Product Category into binary flags: Furniture Office Supplies Technology Enabled easy category-wise analysis

Step 6: Derive New Fields

Used Derive Node Created Profit Margin (%) Formula: (Profit / Sales) × 100

Step 7: Reclassify Fields

Used Reclassify Node Converted Order Priority into numeric levels: Critical → 4 High → 3 Low → 2 Not Specified → 1

Step 8: Create Zone Category

Reclassified Region into Zone_Category Central → North Zone South → South Zone West → West Zone East → East Zone North → North Zone

Step 9: Final Data Merge

Used Merge Node Merged: Aggregated data Category flags Zone category data Used Row ID as the key Applied Full Outer Join Generated one complete, integrated dataset

📈 Final Output

Output: https://github.com/Khushi18Singh/customer-sales-data-transformation-SPSS/blob/main/SPSS_Modeler_Workflow.png.jpeg
The final dataset includes: Total Sales & Profit Record Count Product Category Flags Profit Margin Order Priority Level Zone Category (North, South, East, West) This dataset is fully cleaned, enriched, and analysis-ready.

✅ Learning Outcomes

Hands-on experience with IBM SPSS Modeler Strong understanding of data preprocessing techniques

Learned how to: Remove duplicates Aggregate customer data Engineer new features Convert categorical data for modeling Prepared data for predictive analytics & visualization
