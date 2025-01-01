# Flights Dashboard Using Python, MySQL, and Streamlit
An interactive dashboard for visualizing and analyzing flight data, developed using Python, MySQL, and Streamlit. This project provides real-time insights into flight statuses, routes, delays, and other performance metrics, enabling users to explore various trends and patterns in flight operations.

# Project Features
Real-time Flight Data Visualization: Interactive charts and graphs that display flight routes, delay distributions, and performance metrics.
SQL Queries for Data Extraction: MySQL queries used to efficiently extract, filter, and aggregate data from the MySQL database.
User-Friendly Interface: Built with Streamlit, providing a seamless user experience for exploring the flight data.
Advanced Data Processing: Python libraries such as Pandas for data manipulation and Matplotlib / Plotly for dynamic visualizations.
Installation and Setup
Clone the Repository:

bash
Copy code
git clone https://github.com/your-username/flight-dashboard.git
cd flight-dashboard
Create a Virtual Environment:

bash
Copy code
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install Required Dependencies:

bash
Copy code
pip install -r requirements.txt
Set Up MySQL Database:

Ensure you have MySQL installed and running.
Create a database and import the flight data.
Update the config.py file with your MySQL connection details:
python
Copy code
MYSQL_USER = 'your_username'
MYSQL_PASSWORD = 'your_password'
MYSQL_HOST = 'localhost'
MYSQL_DATABASE = 'flights_db'
Run the Streamlit App:

bash
Copy code
streamlit run app.py
Access the Dashboard:

Open your browser and go to http://localhost:8501 to view the Flights Dashboard.
# Project Structure
app.py: The main Streamlit app where the dashboard is displayed.
config.py: Configuration file for MySQL database connection settings.
requirements.txt: List of Python dependencies required to run the project.
data/: Folder containing the raw flight data and SQL scripts.
images/: Folder with any images used for visualizations or documentation.
Technologies Used
Python: Main programming language used for data processing and backend logic.
MySQL: Relational database used for storing and managing flight data.
Streamlit: Framework used to build the interactive web interface.
Pandas: Data manipulation and analysis library.
Matplotlib & Plotly: Libraries for data visualization.
