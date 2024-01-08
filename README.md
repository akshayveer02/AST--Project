A web scraper to extract job postings from www.indeed.com

Overview:
This project includes a Python script (Indeed.py) designed for web scraping job postings from www.indeed.com. The primary goal is to extract relevant information about Python developer jobs in India and store it efficiently.

Files:
Indeed.py: This Python script contains the web scraping code. It fetches job postings from Indeed, extracts essential details, and stores the data.
Python_India_Jobs.csv: The CSV file contains all the extracted job data. This data is uploaded to the MongoDB database named AST-Project.
main.py: This main Python script showcases the integration of Flask with MongoDB. It establishes a connection and serves as the central point for managing data.

Usage:
Run Indeed.py to initiate the web scraping process.
The extracted job data will be stored in Python_India_Jobs.csv.
Use main.py to connect Flask with MongoDB and manage the stored job data efficiently.

MongoDB Database:
The extracted job data is stored in a MongoDB database named AST-Project, ensuring seamless data management and retrieval.
Feel free to explore, contribute, and enhance the capabilities of this web scraper for your specific needs.
