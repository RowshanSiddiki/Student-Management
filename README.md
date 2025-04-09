# Student-Management

This system is designed to streamline the management and analysis of student records for educational organizations. It leverages MySQL to store, manage, and perform operations on student data. Additionally, Python and libraries like Plotly, Streamlit, and Pandas are used to analyze and present the data in a user-friendly format.
Features:
Add New Students:
A user-friendly interface allows administrators to add new students to the system.
If a student with the same ID already exists in the system, an error message will be displayed to prevent duplication.
Student Performance Analysis:
The system provides a detailed performance analysis of students, displayed as a DataFrame.
Total number of students and their average scores are shown.
Average Score Per Department:
Using SQL JOIN operations, the system calculates the average score per department.
This data is then visualized to provide insights into performance across different departments.
Data Visualization:
The system includes interactive charts:
Bar Chart: Displays the average score per department.
Line Chart: Represents the trend of average scores over time, allowing for performance tracking and analysis.
Technologies Used:
MySQL for database management and data storage.
Python for analysis and building the system logic.
Streamlit for building an interactive web interface for users.
Pandas for handling and manipulating data.
Plotly for creating interactive and visually appealing charts.
How it Works:
Adding a Student: When a new student is added, the system checks the student ID to ensure it does not already exist. If it does, an error is shown.
Data Display: The student performance data is displayed in a structured format using DataFrames, and insights such as total student count and average scores are automatically calculated.
Department-wise Analysis: SQL JOIN operations are utilized to fetch the average score of students in each department and present the results in a visually appealing manner using bar and line charts.
