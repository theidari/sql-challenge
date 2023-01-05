<p align="left">
<img src="https://github.com/theidari/sql-challenge/blob/main/Design/header.png" width="332"><img src="https://github.com/theidari/sql-challenge/blob/main/Design/project_overview.png" width="128"><img src="https://github.com/theidari/sql-challenge/blob/main/Design/code.png" width="128"><img src="https://github.com/theidari/sql-challenge/blob/main/Design/result.png" width="128">
<img src="https://github.com/theidari/sql-challenge/blob/main/Design/reference.png" width="96">
</p>
<p align="center">
<img src="https://github.com/theidari/sql-challenge/blob/main/Design/purple_break_line.png" width="900">
</p>

It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard (a fictional company). Your first major task is to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.

For this project, you’ll design the tables to hold the data from the CSV files, import the CSV files into a SQL database, and then answer questions about the data. That is, you’ll perform data modeling, data engineering, and data analysis, respectively.


This project is divided into three parts:
<p align="center">
$\space \mathtt{\color{purple}1.}$ Data Modeling
$\space \mathtt{\color{purple}2.}$ Data Engineering
$\space \mathtt{\color{purple}3.}$ Data Analysis
</p>


<a href="https://en.wikipedia.org/wiki/Entity%E2%80%93relationship_model"><b>Entity-Relationship Diagrams (ERD)</b></a> was used as basic modeling technique in this project. This technique was performed using <a href="https://www.quickdatabasediagrams.com/"><b>QUICK DBD</b></a> app. ERD identified six employee database entities such as $\space \mathsf{\color{purple}Employees}$, $\space \mathsf{\color{purple}Department} \space \mathsf{\color{purple}Employees}$, $\space \mathsf{\color{purple}Department} \space \mathsf{\color{purple}Managers}$, $\space \mathsf{\color{purple}Salaries}$, $\space \mathsf{\color{purple}Titles}$, $\space \mathsf{\color{purple}Department}$. The result of the modeling was drawn in figure [1].

<p align="center">
<img src="https://raw.githubusercontent.com/theidari/sql-challenge/77abfdda38573ef62a75b2e2326de7114bedfba0/OutputData/Entity%20Relationship%20Diagram/Pewlett_Hackard_ERD.svg" width="760px" height="500px">
</p>
