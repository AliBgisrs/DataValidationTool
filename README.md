# DataValidationTool
Step 1: Understanding the Tool's Functionality
This .pyt script will create a Data Validation Tool in ArcGIS Pro to ensure data consistency across reservoirs, wells, and pipelines. The tool will:

Check Spatial Reference Consistency – Ensure all input layers use the same coordinate system.

Validate Attribute Schema – Ensure required fields exist and match the predefined BP data model.

Enforce Data Version Control – Compare input data with an existing master dataset to track changes.


Step 2: Required Data

To run this tool, you will need:

Input GIS Layers – Feature classes or shapefiles for reservoirs, wells, and pipelines.

Predefined BP Schema – A template dataset (stored in a geodatabase) with the correct field names and data types.

Master Dataset – The authoritative BP GIS database for version control.

Step 3: Run the script

Step 4: How the Tool Works

User Input:

Select an Input Feature Class (Reservoirs, Wells, Pipelines).
Select a Master Dataset for comparison.
Select a Schema Template to validate required fields.
Provide an output path for the Validation Report.
Validation Checks:

Spatial Reference Check: Ensures input data has the correct coordinate system.
Schema Validation: Checks if the input dataset has missing or extra fields.
Version Control: Compares record counts to detect new, missing, or modified data.

Output:

A validation report (.txt) summarizing all findings.


![image](https://github.com/user-attachments/assets/b11f4e94-54cd-4c1d-bd09-e359a8b8c6fc)




Results:

![image](https://github.com/user-attachments/assets/cb11fe3d-8cc4-4cee-a208-51c2ecb6d6b3)
