# Programming-Assignment-4

# README: Experiment 4 - Data Wrangling and Data Visualization

## Intended Learning Outcomes
1. To identify the codes and functions needed in cleaning and visualizing data.
2. To be able to apply and use the different codes and functions in creating a Python program for data wrangling and data visualization.

## Files Included:
- Mindy.csv
- Instru.csv
- DEL CARMEN_PA#4.ipynb

## Problem Statement
Using data wrangling and data visualization techniques with storytelling, analyze the data and present different:
- (i) Data frames
- (ii) Visuals

## Load ECE Board Exam
- Code:

<img width="308" height="44" alt="Screenshot 2025-09-23 at 3 33 14 PM" src="https://github.com/user-attachments/assets/3047f412-1ca6-49bf-8085-82057d982420" />

- Output:

<img width="572" height="510" alt="Screenshot 2025-09-23 at 3 33 54 PM" src="https://github.com/user-attachments/assets/22b336c5-aec3-4d1c-9233-036514783f5f" />
<img width="573" height="283" alt="Screenshot 2025-09-23 at 3 34 10 PM" src="https://github.com/user-attachments/assets/218502af-2f5c-47a9-a142-4a3860209977" />



### Task 1: Create Data Frames
a. **Filename: Instru**  
   - Columns: `["Name", "GEAS", "Electronics >70"]`  
   - Conditions: Track is constant as **Instrumentation**, Hometown is constant as **Luzon**
   - Code that will locate students from Luzon and their track is Instrumentation and has a score greater than 70 in Electronics.
   - Code:
<img width="994" height="61" alt="Screenshot 2025-09-22 at 12 31 22 PM" src="https://github.com/user-attachments/assets/5f53d9d2-629d-4134-976f-656902b2ff53" />

   - Output:
<img width="197" height="95" alt="Screenshot 2025-09-22 at 12 31 47 PM" src="https://github.com/user-attachments/assets/0e51b03a-0845-4e9f-97c1-aad349af1628" />



b. **Filename: Mindy**  
   - Columns: `["Name", "Track", "Electronics", "Average >=55"]`  
   - Conditions: Hometown is constant as **Mindanao**, Gender is constant as **Female**
   - Code that will show students from Mindanao who are female. It also shows the students whose average is greater than or equal to 55.
   - Code:

<img width="984" height="80" alt="Screenshot 2025-09-22 at 12 32 08 PM" src="https://github.com/user-attachments/assets/3a407852-930f-46b0-b8ae-4446227859fe" />
   
   - Output:

<img width="308" height="153" alt="Screenshot 2025-09-22 at 12 32 49 PM" src="https://github.com/user-attachments/assets/e4e17487-20e9-4085-ac8c-a09c59e3ab5f" />





### Task 2: Create a Visualization
- Visualize how different features (chosen track in college, gender, hometown) contribute to the average grade.
- Analyze whether chosen track, gender, or hometown contributes to a higher average score.
- Codes:
- By Track:
- Code that will display a graph that shows the average for each Track.

<img width="615" height="155" alt="Screenshot 2025-09-22 at 12 34 00 PM" src="https://github.com/user-attachments/assets/398e0701-3b91-4553-a866-6e8053d203cf" />

  - Output:

<img width="563" height="453" alt="image" src="https://github.com/user-attachments/assets/ada1cb4b-3bda-4bd0-9ef9-709aadfdd76a" />

  - By Gender:
  - Code that will display a graph that shows the average for each Gender.

<img width="518" height="127" alt="Screenshot 2025-09-23 at 2 39 50 PM" src="https://github.com/user-attachments/assets/765f68eb-0eee-484c-a7a0-cefbd7afe540" />


  - Output:

<img width="563" height="453" alt="image" src="https://github.com/user-attachments/assets/a59cd68b-0c6d-47fa-a779-b8d4fcf02ea9" />


  - By Hometown:
  - Code that will display a graph that shows the average for each Hometown.

<img width="497" height="141" alt="Screenshot 2025-09-22 at 12 37 43 PM" src="https://github.com/user-attachments/assets/e04725ce-e18a-4f7d-92e0-12b662aad910" />

  - Output:

<img width="563" height="453" alt="image" src="https://github.com/user-attachments/assets/ebd2af61-045a-4b35-8004-125fffaf95dd" />

# Conclusion:
- This experiment successfully applied data wrangling and visualization techniques to analyze ECE board exam data. We created filtered dataframes and visualizations to examine how track, gender, and hometown influence academic performance. The exercise demonstrated the power of Python's pandas and matplotlib libraries for transforming raw data into meaningful insights, highlighting the importance of data-driven analysis in identifying trends and patterns for informed decision-making.






