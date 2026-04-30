# College Course Data Analysis: Impact of Attendance on Performance
## Project Overview
This project explores the relationship between student attendance and academic performance in undergraduate mathematics courses. As an adjunct professor teaching Precalculus and Finite Mathematics, I noticed a decline in class attendance in one of my courses and sought to quantify how presence in the classroom correlates with assignment scores and final grades.

The Problem & Motivation
While attendance is not explicitly recorded for these courses, it is a critical component of the learning process. This analysis was motivated by a need for an efficient way to:

* Track Engagement: Determine student attendance based on participation in "proxy" activities like quizzes, exams, and exit slips.

* Correlate Data: Compare attendance frequency with average assignment scores and overall course grades.

* Identify Trends: See if specific student groups (e.g., freshmen vs. seniors) show different patterns in attendance and performance.

## Course Structure & Data Proxies
Since attendance is not taken traditionally, this project uses participation in the following graded components as a proxy for physical presence:

* Quizzes: Administered every Monday to test basics from the previous week.

* Exit Slips: Completed every Wednesday and Friday; these are one-question problems graded on effort to provide immediate feedback and track attendance.

* Exams: Key performance milestones throughout the semester.

* Written Assignments: Hand-written solutions graded for accuracy and work.

* Webwork: Online homework platform assignments focused on accuracy.

## Data Sources
The analysis utilizes two primary data streams:

* Canvas LMS Gradebook: Exported CSV files containing student scores across all assignment categories.

* Course Portal Data: CSV files containing student demographic information, specifically their current class level (Freshman, Sophomore, Junior, or Senior).

** Note on Privacy: To maintain student confidentiality, all data used in this public repository is randomly generated (synthetic) including names. However, the structure and schema of the files remain identical to the original data exported from Canvas and the school portal.**

## Key Questions Addressed
* How many classes did each student actually attend based on completed in-class work?

* Is there a statistically significant difference in final grades between high-attendance and low-attendance students?

* How do different assignment types (Written vs. Webwork) correlate with overall success?

## Technologies Used
* Python: Main programming language.

* Pandas: Data cleaning, manipulation, and calculating assignment averages.

* NumPy: Numerical operations.

* Seaborn & Matplotlib: Data visualization and trend analysis.
