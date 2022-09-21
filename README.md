# United States Marine Corps - Fast, Agile, and Open: Enhanced AI/ML Capabilities with MongoDB
**Project Outline**
- Jupyter notebook: Examples of connecting to a MongoDB instance for analytic purposes.
- ship_analysis.json: full dataset of metadeta embedded documents

# Requirements
- Python 3.9.7
  - pymongo==3.12
  - seaborn
  - pandas
- MongoDB Instance/Atlas (https://www.mongodb.com/docs/atlas/getting-started/)
- MongoDB Compass (https://www.mongodb.com/docs/compass/current/)
- Ship Dataset

User needs to have a MongoDB cluster, links next to Atlas and Compass for getting started.

# Setup
1. Uploaded dataset to MongoDB Atlas cluster
  - Using MongoDB Compass we will upload the JSON into the Atlas cluster: https://www.mongodb.com/docs/compass/current/import-export/
2. Edit jupyter notebook Atlas URI (retrieved from Atlas)
3. Install required libraries
4. Run the code!
5. Explore the data model with compass and modify the aggregation in the Jupyter to transform the data
