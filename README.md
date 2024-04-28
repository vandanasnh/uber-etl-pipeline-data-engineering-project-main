# uber-etl-pipeline-data-engineering-project-main
## Uber Data Analytics with Modern Data Engineering on GCP

This project outlines a process for performing data analytics on ride-hailing trip data (similar to Uber) using Google Cloud Platform (GCP) tools.

**Project Goal:**

* Analyze ride-hailing trip data to gain insights and potentially make data-driven decisions.

**Technologies Used:**

* **Programming Language:** Python
* **Google Cloud Platform (GCP):**
    * **Google Storage:** Cloud storage for the raw trip data.
    * **Compute Engine:** Creates virtual machines to run data processing tasks using Python. 
    * **Mage Data Pipeline Tool:** ([https://mage.ai/](https://mage.ai/)) An open-source tool used to orchestrate and automate the data processing pipeline. Consider contributing to this project if you're interested in open-source development! ([https://github.com/mage-ai/mage-ai](https://github.com/mage-ai/mage-ai))
    * **BigQuery:** A managed data warehouse service for storing and analyzing large datasets.
    * **Looker Studio:** A data visualization tool to create interactive dashboards based on the analyzed data.

**Dataset:**

* **TLC Trip Record Data:** Public dataset from New York City Taxi & Limousine Commission (TLC) containing information on taxi trips. This dataset serves as a substitute for real Uber data, likely due to privacy concerns. It includes details like:
    * Pick-up and drop-off timestamps
    * Locations
    * Trip distances
    * Fares
    * Rate types
    * Payment methods
    * Passenger counts

You can find more information about the dataset here:

* Dataset Download Link: [https://github.com/topics/uber-data](https://github.com/topics/uber-data)
* NYC TLC Trip Record Data Website: [https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
* Data Dictionary: [invalid URL removed]

**Data Model:**

Refer to the video tutorial (link not provided) for details about the data model used to structure and organize the data for analysis.

**Overall Workflow:**

1. **Data Acquisition:** Download or access the TLC trip record data.
2. **Data Preprocessing:** Clean, transform, and prepare the raw data for analysis using Python on a Compute Engine instance. Mage likely orchestrates this process.
3. **Data Storage:** Upload the processed data to BigQuery for efficient storage and querying.
4. **Data Analysis:** Use BigQuery to analyze the data and potentially uncover insights about ride-hailing trip patterns, pricing trends, or other factors.
5. **Data Visualization:** Create dashboards and visualizations using Looker Studio to explore the analyzed data and communicate findings in an interactive way.

This project provides a valuable example of using modern data engineering practices on GCP to analyze ride-hailing data. By following these steps and using the provided video tutorial (link not provided) for detailed guidance, you can gain hands-on experience with data pipelines, cloud storage, data warehousing, and data visualization tools.

 
